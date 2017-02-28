## Linters

It happens to be a major PITA to find these little snippets, so I gather all useful findings here. As a rule of thumb, you should use these as last resort to solve a linting issue.

** Some `JSlint` suppressors work with `JSHint`, YMMV. For `JShint/JSLint` compatibility, `space` after a comment identifier (`/*`) must be omitted.

### ESLint

<http://eslint.org/docs/rules/>

- Suppress all warnings for a single line

```
// eslint-disable-line
```

### JShint

- Suppress environment warnings

```
// jslint browser: true
// jslint jquery: true
// jshint esversion: 6
```

- Suppress undefined global variables. **

```
/*global <var1>, <var2>, ... */
```

- Suppress exported/unused global variables. **

```
/*exported <var1>, <var2>, ... */
```

- Suppress a single warning. Example: `// jshint -W001`

```
// jshint -<*>
// jshint +<*>
```

- Suppress all warnings

```
// jshint ignore:start
// jshint ignore:end
```

- Suppress all warnings for a single line

```
// jshint ignore:line
```

### SCSS-Lint

- Suppress a single warning. Example: `// scss-lint:enable Compass::PropertyWithMixin`

```
// scss-lint:enable <*>
// scss-lint:disable <*>
```

### Pug-lint (was Jade)

<https://github.com/pugjs/pug-lint/blob/master/docs/rules.md>

### Beautify

- Suppress through a section (must be a block-comment)

```
/* beautify ignore:start */
/* beautify ignore:end */
```

## Commands
### Node.js
* Install a package: `$ npm install <pkg>`
* Install a package globally: `$ npm install -g <pkg>`
* Remove a package: `$ npm uninstall <pkg> --save` or `--save-dev` to uninstall from `devDependencies`
* Remove a package globally: `$ npm uninstall -g <pkg>`
* Update all globally installed packages to latest stable version: `$ npm update -g`
* Update all locally installed packages to latest stable version: `$ npm update`
* Update `npm`: `$ npm install -g npm`
* List all globally installed packages: `$ npm list -g`
* List all globally installed packages without dependencies: `$ npm list -g --depth=0`
* List all globally installed outdated packages: `$ npm outdated -g --depth=0`
* List all locally installed packages: `$ npm list`
* List all locally installed packages without dependencies: `$ npm list --depth=0`
* List all locally installed outdated packages: `$ npm outdated --depth=0`
* View version: `$ node -v` or `$ node --version`
* View a package version: `$ npm view <pkg> version`
* Remove `node_modules`: `$ rimraf node_modules`

### Ruby
* Update [RubyGems](https://rubygems.org/pages/download) to latest version: `$ gem update --system`
* List all gems installed: `$ gem list`
* Install a gem: `$ gem install <gem>`
* Uninstall a gem: `$ gem uninstall <gem>`
* Uninstall previous versions of a gem: `$ gem cleanup <gem>`
* Uninstall a specific version of a gem: `$ gem uninstall <gem> --version <version>`
* Uninstall all versions of a gem less than a specific version: `$ gem uninstall <gem> --version '<<version>'`
* Update all gems to latest version: `$ gem update`

## Links
* [Atom Keyboard Shortcuts](https://github.com/nwinkler/atom-keyboard-shortcuts)
* [Brackets Keyboard Shortcuts](https://github.com/adobe/brackets/wiki/Brackets-Shortcuts)
* [GitLab Markdown Documentation](https://github.com/gitlabhq/gitlabhq/blob/master/doc/markdown/markdown.md)
