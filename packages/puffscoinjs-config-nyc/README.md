# @puffscoinjs/config-nyc

Common test coverage configuration for `PuffscoinJS` libraries.

Tool: [nyc](https://istanbul.js.org/)

Supported Version: `^11.7.0`

Exposed CLI commands:

- `puffscoinjs-config-coverage`
- `puffscoinjs-config-coveralls`

## Usage

Add `.nycrc`:

```json
{
  "extends": "@puffscoinjs/config-nyc"
}
```

Use CLI commands above in `package.json`:

```json
  "scripts": {
    "coverage": "puffscoinjs-config-coverage",
    "coveralls": "puffscoinjs-config-coveralls"
  }
```



