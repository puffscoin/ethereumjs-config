# @puffscoinjs/config-prettier

Common formatting configuration for `PuffscoinJS` libraries.

Tool: [Prettier](https://prettier.io/)

Supported Version: `^1.15.3`

Exposed CLI commands:

- `puffscoinjs-config-format`
- `puffscoinjs-config-format-fix`

## Usage

Add `prettier.config.js`:

```javascript
module.exports = require('@puffscoinjs/config-prettier')
```

Add `.prettierignore`:

```shell
node_modules
.vscode
package.json
dist
.nyc_output
```

Use CLI commands above in `package.json`:

```json
  "scripts": {
    "format": "puffscoinjs-config-format",
    "format-fix": "puffscoinjs-config-format-fix"
  }
```



