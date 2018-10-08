# eslint-config-mojiscript

ESLint config file for [MojiScript](https://github.com/joelnet/MojiScript).

## Install

```bash
npm install --save-dev eslint-config-mojiscript eslint-plugin-fp@2.3.0 eslint-plugin-prefer-arrow@1.1.3 eslint-plugin-better@0.1.5
```

Copy [`.eslintignore`](.eslintignore) to the root of your app.

```
__tests__/
coverage/
interop/
*.test.js
*.test.mjs
```

Create an `.eslintrc.yml` file.

```yaml
extends: "mojiscript"
```
