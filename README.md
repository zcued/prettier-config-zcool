# @zcool/prettier-config

ZCOOL FE Prettier Configuration. See all prettier config options [here](https://prettier.io/docs/en/options.html).

## Usage
**Install**:
```bash
$ yarn add -D @zcool/prettier-config prettier
```

**Add `.stylelintrc.js`**
  ```js
  module.exports = {
    extends: '@zcool/stylelint-config/sc',
    rules: {
      'value-keyword-case': null,
    },
  }
  ```

**Remove old `.prettierrc` file**

## Contribute
1. fork
2. modify index.json
3. create merge request