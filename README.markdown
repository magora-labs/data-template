# data-template

**_A template for assets data-packages_**

```
Stability: 1 - Experimental
```

**basics**

 - `.eslintrc` & `.eslintignore` - style rules closely follow google's javascript style guide
 - `.sass-lint.yml`
 - `.gitignore` & `.npmignore`
 - MIT [LICENSE](./LICENSE)
 - a index.mustache

**package.json scripts**

 - `npm test` - eslint + sass-lint + istanbul + mocha
 - `npm install` - will add a pre-commit hook which runs `npm test` (existing hooks will be overwritten)
 - `npm run lint` - eslint + sass-lint
 - `npm run update` - next-update
 - `npm run log` - generate a markdown formatted changelog
 - `npm run clean` - rm `coverage/`, `node_modules`, `npm-debug.log`

[**Download**](https://github.com/magora-labs/data-template/archive/master.zip)

## Tests

```bash
npm test
firefox coverage/lcov-report/index.html
```

### Coverage

```
Statements   : XX.XX% ( YY/ZZ )
Branches     : XX.XX% ( YY/ZZ )
Functions    : XX.XX% ( YY/ZZ )
Lines        : XX.XX% ( YY/ZZ )
```
