# Commands

## Git Submodules

Via GitBash:

- To add: navigate to designated path and run:

  ```
  $ git submodule add <PATH-TO-REPOSITORY> // E.g.: https://github.com/adi518/cheatsheet
  ```

- Removal

  ```
  $ git rm --cached <REPOSITORY-FOLDER>
  rm -rf .git/modules/<REPOSITORY-FOLDER>
  ```

## Node.js

- Install a package: `$ npm install <pkg>`
- Install a package globally: `$ npm install -g <pkg>`
- Remove a package: `$ npm uninstall <pkg> --save` or `--save-dev` to remove from `devDependencies`
- Remove a package globally: `$ npm uninstall -g <pkg>`
- Update all globally installed packages to latest stable version: `$ npm update -g`
- Update all locally installed packages to latest stable version: `$ npm update`
- Update Npm: `$ npm install -g npm`
- List all globally installed packages: `$ npm list -g`
- List all globally installed packages without dependencies: `$ npm list -g --depth=0`
- List all globally installed outdated packages: `$ npm outdated -g --depth=0`
- List all locally installed packages: `$ npm list`
- List all locally installed packages without dependencies: `$ npm list --depth=0`
- List all locally installed outdated packages: `$ npm outdated --depth=0`
- View version: `$ node -v` or `$ node --version`
- View a package version: `$ npm view <pkg> version`
- Remove `node_modules`: `$ rimraf node_modules`
- Init a new project with [default configuration](https://docs.npmjs.com/cli/init): `npm init -y`

## Ruby

- Update [RubyGems](https://rubygems.org/pages/download) to latest version: `$ gem update --system`
- List all gems installed: `$ gem list`
- Install a gem: `$ gem install <gem>`
- Remove a gem: `$ gem uninstall <gem>`
- Remove previous versions of a gem: `$ gem cleanup <gem>`
- Remove a specific version of a gem: `$ gem uninstall <gem> --version <version>`
- Remove all versions of a gem below a given version: `$ gem uninstall <gem> --version '<<version>'`
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

# Links

- [VS Code Keyboard Shortcuts](https://code.visualstudio.com/docs/customization/keybindings)
- [Atom Keyboard Shortcuts](https://github.com/nwinkler/atom-keyboard-shortcuts)
- [Brackets Keyboard Shortcuts](https://github.com/adobe/brackets/wiki/Brackets-Shortcuts)
- [Git Markdown Documentation](http://daringfireball.net/projects/markdown/)
- [GitLab Markdown Documentation](https://github.com/gitlabhq/gitlabhq/blob/master/doc/user/markdown.md)

- Git Submodules

    - <https://git.wiki.kernel.org/index.php/GitSubmoduleTutorial#Removal>
    - <http://stackoverflow.com/questions/1260748/how-do-i-remove-a-submodule>
    - <http://stackoverflow.com/questions/12898278/issue-with-adding-common-code-as-git-submodule-already-exists-in-the-index>
