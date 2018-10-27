# Slints VSCode Snippets

[![Version](https://vsmarketplacebadge.apphb.com/version/slints.SlintsVSCodeSnippets.svg)](https://vsmarketplacebadge.apphb.com/version-short/dsznajder.es7-react-js-snippets.svg)
[![Install](https://vsmarketplacebadge.apphb.com/installs/slints.SlintsVSCodeSnippets.svg)](https://vsmarketplacebadge.apphb.com/installs-short/dsznajder.es7-react-js-snippets.svg)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating-short/slints.SlintsVSCodeSnippets.svg)](https://vsmarketplacebadge.apphb.com/rating-short/dsznajder.es7-react-js-snippets.svg)

This extension provide you Javascript, React, and GraphQL (Apollo v2.0) snippets in ES7 with babel plugins features used by Slints Team for [VS Code](https://code.visualstudio.com/)

Here is direct link to marketplace [	
Slints VSCode Snippets](https://marketplace.visualstudio.com/items?itemName=slints.SlintsVSCodeSnippets)

## Supported languages (file extensions)

- JavaScript (.js)
- JavaScript React (.jsx)


## Basic Methods

| Prefix  | Method                                              |
| ------: | --------------------------------------------------- |
| `imp→`  | `import moduleName from 'module'`                   |
| `imn→`  | `import 'module'`                                   |
| `imd→`  | `import { destructuredModule } from 'module'`       |
| `ime→`  | `import * as alias from 'module'`                   |
| `ima→`  | `import { originalName as aliasName} from 'module'` |
| `exp→`  | `export default moduleName`                         |
| `exd→`  | `export { destructuredModule } from 'module'`       |
| `exa→`  | `export { originalName as aliasName} from 'module'` |
| `enf→`  | `export const functionName = (params) => { }`       |
| `edf→`  | `export default (params) => { }`                    |
| `met→`  | `methodName = (params) => { }`                      |
| `fre→`  | `arrayName.forEach(element => { }`                  |
| `fof→`  | `for(let itemName of objectName { }`                |
| `fin→`  | `for(let itemName in objectName { }`                |
| `anfn→` | `(params) => { }`                                   |
| `nfn→`  | `const functionName = (params) => { }`              |
| `dob→`  | `const {propName} = objectToDescruct`               |
| `dar→`  | `const [propName] = arrayToDescruct`                |
| `sti→`  | `setInterval(() => { }, intervalTime`               |
| `sto→`  | `setTimeout(() => { }, delayTime`                   |
| `prom→` | `return new Promise((resolve, reject) => { }`       |
| `cmmb→` | `comment block`                                     |
| `cp→`   | `const { } = this.props`                            |
| `cs→`   | `const { } = this.state`                            |

## React

| Prefix      | Method                                                                              |
| ----------: | ----------------------------------------------------------------------------------- |
| `imr→`      | `import React from 'react'`                                                         |
| `imrd→`     | `import ReactDOM from 'react-dom'`                                                  |
| `imrc→`     | `import React, { Component } from 'react'`                                          |
| `imrcp→`    | `import React, { Component } from 'react' & import PropTypes from 'prop-types'`     |
| `imrpc→`    | `import React, { PureComponent } from 'react'`                                      |
| `imrpcp→`   | `import React, { PureComponent } from 'react' & import PropTypes from 'prop-types'` |
| `imrm→`    | `import React, { memo } from 'react'`                                      |
| `imrmp→`   | `import React, { memo } from 'react' & import PropTypes from 'prop-types'` |
| `impt→`     | `import PropTypes from 'prop-types'`                                                |
| `rconst→`   | `constructor(props) with this.state`                                                |
| `rconc→`    | `constructor(props, context) with this.state`                                       |
| `est→`      | `this.state = { }`                                                                  |
| `cdm→`      | `componentDidMount = () => { }`                                                     |
| `scu→`      | `shouldComponentUpdate = (nextProps, nextState) => { }`                             |
| `cdup→`     | `componentDidUpdate = (prevProps, prevState) => { }`                                |
| `cwun→`     | `componentWillUnmount = () => { }`                                                  |
| `cwun→`     | `componentWillUnmount = () => { }`                                                  |
| `gdsfp→`    | `static getDerivedStateFromProps(nextProps, prevState) { }`                         |
| `gsbu→`     | `getSnapshotBeforeUpdate = (prevProps, prevState) => { }`                           |
| `ren→`      | `render() { return( ) }`                                                            |
| `sst→`      | `this.setState({ })`                                                                |
| `ssf→`      | `this.setState((state, props) => return { })`                                       |
| `props→`    | `this.props.propName`                                                               |
| `state→`    | `this.state.stateName`                                                              |
| `rcontext→` | `const ${1:contextName} = React.createContext()`                                    |
| `cref→`     | `this.${1:refName}Ref = React.createRef()`                                          |
| `fref→`     | `const ref = React.createRef()`                                                     |
| `bnd→`      | `this.methodName = this.methodName.bind(this)`                                      |

## React Native

| Prefix     | Method                                 |
| ---------: | -------------------------------------- |
| `imrn→`    | `import { $1 } from 'react-native'`    |
| `rnstyle→` | `const styles = StyleSheet.create({})` |


## PropTypes

| Prefix    | Method                                   |
| --------: | ---------------------------------------- |
| `pta→`    | `PropTypes.array`                        |
| `ptar→`   | `PropTypes.array.isRequired`             |
| `ptb→`    | `PropTypes.bool`                         |
| `ptbr→`   | `PropTypes.bool.isRequired`              |
| `ptf→`    | `PropTypes.func`                         |
| `ptfr→`   | `PropTypes.func.isRequired`              |
| `ptn→`    | `PropTypes.number`                       |
| `ptnr→`   | `PropTypes.number.isRequired`            |
| `pto→`    | `PropTypes.object`                       |
| `ptor→`   | `PropTypes.object.isRequired`            |
| `pts→`    | `PropTypes.string`                       |
| `ptsr→`   | `PropTypes.string.isRequired`            |
| `ptnd→`   | `PropTypes.node`                         |
| `ptndr→`  | `PropTypes.node.isRequired`              |
| `ptel→`   | `PropTypes.element`                      |
| `ptelr→`  | `PropTypes.element.isRequired`           |
| `pti→`    | `PropTypes.instanceOf(name)`             |
| `ptir→`   | `PropTypes.instanceOf(name).isRequired`  |
| `pte→`    | `PropTypes.oneOf([name])`                |
| `pter→`   | `PropTypes.oneOf([name]).isRequired`     |
| `ptet→`   | `PropTypes.oneOfType([name])`            |
| `ptetr→`  | `PropTypes.oneOfType([name]).isRequired` |
| `ptao→`   | `PropTypes.arrayOf(name)`                |
| `ptaor→`  | `PropTypes.arrayOf(name).isRequired`     |
| `ptoo→`   | `PropTypes.objectOf(name)`               |
| `ptoor→`  | `PropTypes.objectOf(name).isRequired`    |
| `ptsh→`   | `PropTypes.shape({ })`                   |
| `ptshr→`  | `PropTypes.shape({ }).isRequired`        |
| `ptany→`  | `PropTypes.any`                          |
| `ptypes→` | `static propTypes = {}`                  |


## Console

| Prefix | Method                              |
| -----: | ----------------------------------- |
| `clg→` | `console.log(object)`               |
| `cas→` | `console.assert(expression,object)` |
| `ccl→` | `console.clear()`                   |
| `cco→` | `console.count(label)`              |
| `cdi→` | `console.dir`                       |
| `cer→` | `console.error(object)`             |
| `cgr→` | `console.group(label)`              |
| `cge→` | `console.groupEnd()`                |
| `ctr→` | `console.trace(object)`             |
| `cwa→` | `console.warn`                      |
| `cin→` | `console.info`                      |

## React Components

### `rcc`

Create a react component class

```javascript
import React, { Component } from 'react';
import s from './styles.js';

class MyComponent extends Component {
  render() {
    return (
      <s.Wrapper>
        $0
      </s.Wrapper>
    );
  }
}

export default MyComponent;
```

### `rccq`

Create a react component class with Apollo GraphQL Query

```javascript
import React, { Component } from 'react';
import gql from 'graphql-tag';
import { Query } from 'react-apollo';
import s from './styles.js';

const QUERY = gql`
  query doQuery {
    
  }
`;

class MyComponent extends Component {
  render() {
    return (
      <Query query={QUERY}>
        {( { data, loading, error } ) => {
          return (
            <s.Wrapper>
              $0
            </s.Wrapper>
          );
        }}
      </Query>
    );
  }
}

export default MyComponent;
```

### `rccm`

Create a react component class with Apollo GraphQL Mutation

```javascript
import React, { Component } from 'react';
import gql from 'graphql-tag';
import { Mutation } from 'react-apollo';
import s from './styles.js';

const MUTATION = gql`
  mutation doMutation {
    $0
  }
`;

class MyComponent extends Component {
  render() {
    return (
      <Mutation query={MUTATION}>
        {(mutate, { loading, error } ) => {
          return (
            <s.Wrapper>
              
            </s.Wrapper>
          );
        }}
      </Mutation>
    );
  }
}

export default MyComponent;
```
