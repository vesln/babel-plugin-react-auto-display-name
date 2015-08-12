# babel-plugin-react-auto-display-name

Add displayName to React.createClass calls.

## Installation

```sh
$ npm install babel-plugin-react-auto-display-name
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["react-auto-display-name"]
}
```

### Via CLI

```sh
$ babel --plugins react-auto-display-name script.js
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  plugins: ["react-auto-display-name"]
});
```

## License

MIT
