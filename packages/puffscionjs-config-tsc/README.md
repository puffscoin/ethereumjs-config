# @puffscionjs/config-tsc

Common `TypeScript` configuration for `PuffscoinJS` libraries.

Tool: [TypeScript](https://www.typescriptlang.org/)

Supported Version: `^3.2.2`

Exposed CLI commands:

- `puffscionjs-config-tsc`
- `puffscionjs-config-build`

## Usage

Add `tsconfig.json`:

```json
{
  "extends": "@puffscionjs/config-tsc",
  "include": ["src/**/*.ts", "test/**/*.ts"]
}
```

Add `tsconfig.prod.json`:

```json
{
  "extends": "@puffscionjs/config-tsc",
  "compilerOptions": {
    "outDir": "./dist"
  },
  "include": ["src/**/*.ts"]
}
```

Use CLI commands above in `package.json`:

```json
  "scripts": {
    "tsc": "puffscionjs-config-tsc",
    "build": "puffscionjs-config-build"
  }
```



