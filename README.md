# JetBrains LiveTemplates

Init this repo in your [template folder](https://www.jetbrains.com/help/idea/2016.2/sharing-live-templates.html#config_file_location) of your IDEA / Webstorm / PhpStorm IDE

* [Javascript](#javascript)
  * [Console](#console)
* [MobX](#mobx)
* [React](#react)
* [JSX control statements](#jsx-control-statements)

## Javascript

#### `des`

Insert ES6 **des**tructuring statement:

```js
const {field} = variable;
```

#### `im`

Insert **im**port statement:
(Type: 1. modulePath, 2. moduleName)

```js
import moduleName from "modulePath";
```

#### `fn`

Insert **f**unctio**n** expression:

```js
function functionName(params) {

}
```

#### `af`

Insert **a**rrow-**f**unction:

```js
(parameter) => {}
```

#### `afn`

Insert **a**nonymous-**f**unctio**n**:

```js
function (params) {

}
```

#### `cf`

Insert function in class scope (**c**lass-**f**unction):

```js
functionName(params) {

}
```

#### `caf`

Insert arrow function in class scope (**c**lass-**a**rrow-**f**unction):

```js
functionName = (params) => {

};
```

#### `iife`

Insert a **i**mmediately **i**nvoked **f**unction **e**xpression:
(Can be used to wrap current selection)

```js
(function () {
  
})();
```

#### `edc`

Insert a **e**xport **d**efault **c**lass statement:

```js
export default class className {

}
```

#### `edf`

Insert a **e**xport **d**efault **f**unction statement:

```js
export default function (params) {

}
```

### Console

#### `cl`

Insert **c**onsole.**l**og statement:

```js
console.log("message");
```

#### `clv`

Insert **c**onsole.**l**og statement with **v**ariable:

```js
console.log("variable:", variable);
```

#### `cc`

Insert **c**onsole.**c**ount statement:

```js
console.count("message");
```

#### `cw`

Insert **c**onsole.**w**arn statement:

```js
console.warn("message");
```

#### `cd`

Insert **c**onsole.**d**ebug statement:

```js
console.debug("message");
```

#### `cd`

Insert **c**onsole.**d**ebug statement with **v**ariable:

```js
console.debug("variable:", variable);
```

## MobX

#### `ms`

Insert **M**obX **S**tore template:

```js
import {observable, computed, action} from "mobx";

export default class className {

}
```

## React

#### `rlc`
inserts **R**eact **L**ife**C**ycle-method:
* `componentWillMount`
* `componentDidMount`
* `componentWillReceiveProps`
* `shouldComponentUpdate`
* `componentWillUpdate`
* `componentDidUpdate`
* `componentWillUnmount`

#### `comp` 

Insert **R**eact **C**omponent:

```js
import React, {Component} from "react";
import PropTypes from "prop-types";

export default class $componentName$ extends Component {
  static propTypes = {

  };

  render() {
    return (
      <div>
        
      </div>
    );
  }
}
```

#### `rc`

Insert **R**eact **C**onstructor:

```js
constructor(props) {
  super(props);
}
```

#### `pt`

Insert **P**rop**T**ype definition (see: [React Docs: Component](https://facebook.github.io/react/docs/react-component.html)):

```js
propName: PropTypes.type
```

## [JSX control statements](https://github.com/AlexGilleran/jsx-control-statements)

#### `for`

```html
<For each="item" of={collection} index="index">

</For>
```

#### `if`

```html
<If condition={condition}>

</If>
```

#### `choose`

```html
<Choose> 
  <When condition={$condition$}></When>
  <Otherwise></Otherwise>
</Choose>
```
