## Commands
### Git Submodules
Open GitBash in submodule designated path and enter:
```
$ git submodule add <PATH-TO-REPOSITORY>
```

### Node.js
* Install a package: `$ npm install <pkg>`
* Install a package globally: `$ npm install -g <pkg>`
* Remove a package: `$ npm uninstall <pkg> --save` or `--save-dev` to remove from `devDependencies`
* Remove a package globally: `$ npm uninstall -g <pkg>`
* Update all globally installed packages to latest stable version: `$ npm update -g`
* Update all locally installed packages to latest stable version: `$ npm update`
* Update Npm: `$ npm install -g npm`
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
* Remove a gem: `$ gem uninstall <gem>`
* Remove previous versions of a gem: `$ gem cleanup <gem>`
* Remove a specific version of a gem: `$ gem uninstall <gem> --version <version>`
* Remove all versions of a gem below a given version: `$ gem uninstall <gem> --version '<<version>'`
* Update all gems to latest version: `$ gem update`

## Links
* [Atom Keyboard Shortcuts](https://github.com/nwinkler/atom-keyboard-shortcuts)
* [Brackets Keyboard Shortcuts](https://github.com/adobe/brackets/wiki/Brackets-Shortcuts)
* [GitLab Markdown Documentation](https://github.com/gitlabhq/gitlabhq/blob/master/doc/user/markdown.md)
