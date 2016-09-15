# JetBrains LiveTemplates

init this repo in your [template folder](https://www.jetbrains.com/help/idea/2016.2/sharing-live-templates.html#config_file_location) of your IDEA / Webstorm / PhpStorm IDE

* [Javascript](#javascript)
* [React](#react)
* [JSX control statements](#jsx-control-statements)

## Javascript

### `des`

```js
const {field} = variable;
```

### `cl`

```js
console.log("message");
```

### `clv`

```js
console.log("variable", variable);
```

### `cc`

```js
console.count("message");
```

### `af`

```js
(parameter) => {}
```

## React

### `rlc`
* inserts react LifeCycle-method:
  * `componentWillMount`
  * `componentDidMount`
  * `componentWillReceiveProps`
  * `shouldComponentUpdate`
  * `componentWillUpdate`
  * `componentDidUpdate`
  * `componentWillUnmount`

### `comp` 

```js
import React, {Component, PropTypes} from "react";

export default class FileName extends Component {
  static propTypes = {
  
  };

  render() {
    return(
    	<div>
    	
      </div>
    )
  }
}
```

### `rc`

```js
constructor(props) {
  super(props);
}
```

### `pt`

* type is on of the following: func, object, array, bool, number, string

```js
propName: PropTypes.type
```

## [JSX control statements](https://github.com/AlexGilleran/jsx-control-statements)

### `for`

```html
<For each="item" of={collection} index="index">

</For>
```

### `if`

```html
<If condition={condition}>

</If>
```

### `choose`

```html
<Choose> 
  <When condition={$condition$}></When>
  <Otherwise></Otherwise>
</Choose>
```
