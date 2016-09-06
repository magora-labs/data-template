# data-template

**_A template for assets data-packages_**

```
Stability: 1 - Experimental
```

**basics**

 - `.eslintrc` & `.eslintignore` - style rules closely follow google's javascript style guide
 - `.gitignore` & `.npmignore`
 - `bower.json` & `.bowerrc`
 - MIT [LICENSE](./LICENSE)
 - a `index.mustache` in the *default* theme

**package.json scripts**

 - `npm test` - eslint
 - `npm install`
   - runs `bower i` and
   - will add a pre-commit hook which runs `npm test` (existing hooks will be overwritten)
 - `npm run lint` - eslint
 - `npm run log` - generate a markdown formatted changelog
 - `npm run clean` - rm `node_modules`, `npm-debug.log`

**bower**

If you want to use *bower*, please install it globally
```
npm i -g bower
```
if *not* you can safely follow these steps

  - remove `bower i` from the [postinstall script](./package.json) and
  - remove the [`.bowerrc`](./.bowerrc) and [`bower.json`](./bower.json) files

[**Download**](https://github.com/magora-labs/data-template/archive/master.zip)
