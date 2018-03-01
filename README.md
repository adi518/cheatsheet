# Commands

## Git Submodules

Via GitBash:

- To add: navigate to designated path and run:

  ```
  $ git submodule add <PATH-TO-REPOSITORY> // E.g.: `https://github.com/adi518/cheatsheet`
  ```

- Removal

  ```
  $ git rm --cached <REPOSITORY-FOLDER> // E.g. `cheatsheet`
  rm -rf .git/modules/<REPOSITORY-FOLDER>
  ```

## Node.js

- Install a package: `$ npm install <package> -S` or `-D` to add to `devDependencies`
- Install a package globally: `$ npm install -g <package>`
- Install a specific package version: `$ npm install <package>@<version>`
- Remove a package: `$ npm rm <package> -S` or `-D` to remove from `devDependencies`
- Remove a package globally: `$ npm uninstall -g <package>`
- Update all globally installed packages to latest stable version: `$ npm up -g`
- Update all locally installed packages to latest stable version: `$ npm up`
- Update Npm: `$ npm install -g npm`
- List all globally installed packages: `$ npm ls -g`
- List all globally installed packages without their dependencies: `$ npm ls -g --depth=0`
- List all globally installed outdated packages: `$ npm outdated -g --depth=0`
- List all locally installed packages: `$ npm ls`
- List all locally installed packages without their dependencies: `$ npm ls --depth=0`
- List all locally installed development packages without their dependencies: `$ npm ls --dev --depth=0`
- List all locally installed outdated packages: `$ npm outdated --depth=0`
- View Npm package versions: `$ npm view <package> versions`
- View Npm version: `$ node -v` or `$ node --version`
- View a package version: `$ npm view <package> version`
- Remove `node_modules`: `$ rimraf node_modules` (requires global module [rimraf](https://www.npmjs.com/package/rimraf))
- Init a new project with [default configuration](https://docs.npmjs.com/cli/init): `npm init -y`

## Installing Npm package from Git
```
npm install git+ssh://git@github.com:<githubname>/<githubrepo.git[#<commit-ish>]
npm install git+ssh://git@github.com:<githubname>/<githubrepo.git>[#semver:^x.x]
npm install git+http://git@github.com/<githubname>/<githubrepo.git>
npm install git+https://git@github.com/<githubname>/<githubrepo.git>
npm install git://github.com/<githubname>/<githubrepo.git>
npm install github:<githubname>/<githubrepo>[#<commit-ish>]
```

## Ruby

- Update [RubyGems](https://rubygems.org/pages/download) to latest version: `$ gem update --system`
- List all gems installed: `$ gem list`
- Install a gem: `$ gem install <package>`
- Remove a gem: `$ gem uninstall <package>`
- Remove previous versions of a gem: `$ gem cleanup <package>`
- Remove a specific version of a gem: `$ gem uninstall <package> --version <version>`
- Remove all versions of a gem below a given version: `$ gem uninstall <package> --version '<<version>'`
- Update all gems to latest version: `$ gem update`

# Hotkeys

## Atom

- Format: `CTRL + ALT + B`
- Duplicate line: `CTRL + SHIFT + D`
- Move line: `CTRL + UP/DOWN`
- Fold: `SHIFT + CTRL + ALT + [`
- Expand: `SHIFT + CTRL + ALT + ]`

## VS Code

- Format: `SHIFT + ALT + F`
- Duplicate line: `SHIFT + ALT + UP/DOWN`
- Move line: `ALT + UP/DOWN`
- Fold: `CTRL + K, CTRL + 0`
- Expand: `CTRL + K, CTRL + J`

# Markdown
<pre>
```json
   // code for coloring
```
```html
   // code for coloring
```
```js
   // code for coloring
```
```css
   // code for coloring
```
// etc.
</pre>

# Links

* [VS Code Keyboard Shortcuts](https://code.visualstudio.com/docs/customization/keybindings)
* [Atom Keyboard Shortcuts](https://github.com/nwinkler/atom-keyboard-shortcuts)
* [Brackets Keyboard Shortcuts](https://github.com/adobe/brackets/wiki/Brackets-Shortcuts)
* [Git Markdown Documentation](http://daringfireball.net/projects/markdown/)
* [GitLab Markdown Documentation](https://github.com/gitlabhq/gitlabhq/blob/master/doc/user/markdown.md)

- Git Submodules

  * [GitSubmoduleTutorial](https://git.wiki.kernel.org/index.php/GitSubmoduleTutorial#Removal)
  * [how-do-i-remove-a-submodule](http://stackoverflow.com/questions/1260748/how-do-i-remove-a-submodule)
  * [issue-with-adding-common-code-as-git-submodule-already-exists-in-the-index](http://stackoverflow.com/questions/12898278/issue-with-adding-common-code-as-git-submodule-already-exists-in-the-index)
  * https://stackoverflow.com/questions/17509669/how-to-install-an-npm-package-from-github-directly
  * [how-to-add-color-to-githubs-readme-md-file](https://stackoverflow.com/questions/11509830/how-to-add-color-to-githubs-readme-md-file)