# react-inject-props-decorator
ES7 decorator to inject props in your react component methods.

## Install

```sh
$ npm install --save react-inject-props-decorator
```
or

```sh
$ yarn add react-inject-props-decorator
```

## Usage Example

```javascript
import React, { Component }
import injectProps from 'react-inject-props-decorator';

class HelloUser extends Component {

  @injectProps
  render({firstName, lastName}) {
    <div>Hello {firstName} {lastName}</div>
  }
}
```
