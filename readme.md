# ng-tslint

This is a NPM package with some custom rules for your tslint configuration.
The focus of this configuration is on [angluar](https://angular.io/) projects and extend the [codelizer](https://github.com/mgechev/codelyzer) package.

## How Install it

Install like a dev dependency the package via npm or yarn:

NPM command

```bash
npm i @coara/ng-tslint -D
```

or Yarn conmand

```bash
yarn add @coara/ng-tslint -D
```

### Configuration

Then you should extend your current `tslint.json` with this new configuration:

```json
{
  "extends": "@coara/ng-tslint/tslint-config",
  "linterOptions": {
    "exclude": ["**/some_folder/**"]
  },
  "rules": {
      ...
  }
}
```

---

Package powered by [coara TM](https://coara.co)
