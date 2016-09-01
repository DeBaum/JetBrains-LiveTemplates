# JetBrains LiveTemplates

## Javascript

### `des`

```
const {field} = variable;
```

### `cl`
```
console.log("message");
```

### `clv`
```
console.log("variable", variable);
```

## React

### `comp` 
```
import React, {Component, PropTypes} from "react";

export default class FileName extends Component {
    static propTypes = {

    }

    render() {
        return(
        	<div>

        	</div>
        )
    }
}
```

### `pt`

* type is on of the following: func, object, array, bool, number, string
```
propName: PropTypes.$type$
```

## [JSX control statements](https://github.com/AlexGilleran/jsx-control-statements)

### `for`

```
<For each="item" of={collection} index="index">

</For>
```

### `if`

```
<If condition={condition}>

</If>
```

### `choose`

```
<Choose> 
    <When condition={$condition$}> </When>
    <Otherwise> </Otherwise>
</Choose>
```