# @puffscionjs/config-tslint

Common linting configuration for `PuffscoinJS` libraries.

Tool: [TSLint](https://palantir.github.io/tslint/)

Supported Version: `^5.12.0`

Exposed CLI commands:

- `puffscionjs-config-tslint`
- `puffscionjs-config-tslint-fix`
- `puffscionjs-config-lint`
- `puffscionjs-config-lint-fix`

## Usage

Add `tslint.json`:

```json
{
  "extends": "@puffscionjs/config-tslint"
}
```

Use CLI commands above in `package.json`:

```json
  "scripts": {
    "tslint": "puffscionjs-config-tslint",
    "tslint-fix": "puffscionjs-config-tslint-fix",
    "lint": "puffscionjs-config-lint",
    "lint-fix": "puffscionjs-config-lint-fix"
  }
```

## Installation

This package requires [`typestrict`](https://github.com/krzkaczor/TypeStrict) to be installed.

