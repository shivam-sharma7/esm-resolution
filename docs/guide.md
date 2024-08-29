## How to add in your project?

You can use npm or yarn in order to add in your project. Run one of the following commands in your terminal:

```bash
# Using npm
npm install esm-resolution

# Using yarn
yarn add esm-resolution
```

## Usage

After installing the package, you can import and use it in your project. Below are examples of how to use it with both ES Modules and CommonJS.

### ES modules

If you are using ES Modules, you can import the package as follows

```javascript
// index.mjs
import { myFunction } from 'esm-resolution';

myFunction();
```

### CommonJS

If you are using CommonJS, you can require the package as follows:

```javascript
// index.cjs
const { myFunction } = require('esm-resolution');

myFunction();
```
