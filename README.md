# react-inject-props-decorator
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![npm version](https://img.shields.io/npm/v/react-inject-props-decorator.svg?style=flat-square)](https://www.npmjs.com/package/react-inject-props-decorator)

ES7 decorator to inject props in your react component methods.

## Install

```sh
$ npm i -S react-inject-props-decorator
```
or

```sh
$ yarn add react-inject-props-decorator
```

## Example

```javascript
import React, { Component } from 'react';
import injectProps from 'react-inject-props-decorator';

class HelloUser extends Component {

  @injectProps
  render({firstName, lastName}) {
    return (
      <div>Hello {firstName} {lastName}</div>
    )
  }
}
```
## License

[MIT](LICENSE)
