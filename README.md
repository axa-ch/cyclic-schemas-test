# Cyclic JSON schema References Reproduction

This repo is reproduction for:
https://github.com/adobe/jsonschema2md/issues/185

## How to reproduce

1. `git clone` ...
2. `npm i`
3. `npm run test`

Result:

```sh
npm run test

> cyclic-schemas-test@1.0.0 test .../dev/cyclic-schemas-test
> jsonschema2md -o docs/ -x docs/ -d schemas/ -e json

loading schemas
# CLI freezes at this point
```