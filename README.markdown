# data-template

**_A template for assets data-packages_**

```
Stability: 1 - Experimental
```

- [`ChangeLog`](./CHANGELOG.markdown)


**basics**

 - `.eslintrc` & `.eslintignore` - style rules closely follow google's javascript style guide
 - `.gitignore` & `.npmignore`
 - `bower.json` & `.bowerrc`
 - MIT [LICENSE](./LICENSE)
 - a `index.mustache` in the *default* theme

**package.json scripts**

 - `npm test` - eslint, istanbul + nyc and mocha
 - `npm run lint` - eslint
 - `npm run log` - generate a markdown formatted changelog
 - `npm run clean` - rm `node_modules`, `npm-debug.log`, `bower_componets`, `coverage`, `.nyc_output`

**bower**

If you want to use *bower*, please install it globally
```
npm i -g bower
```
if *not* you can safely follow these steps

  - remove `bower i` from the [postinstall script](./package.json),
  - remove `&& rm -rf www/themes/default/misc/bower_components/` from the [clean script](./package.json) and
  - remove the [`.bowerrc`](./.bowerrc) and [`bower.json`](./bower.json) files

[**Download**](https://github.com/magora-labs/data-template/archive/master.zip)

## Tests

```
Branches     : Unknown% ( 0/0 )
Statements   : Unknown% ( 0/0 )
Functions    : Unknown% ( 0/0 )
Lines        : Unknown% ( 0/0 )
```
