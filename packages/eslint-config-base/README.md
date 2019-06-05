# @labkey/eslint-config-base

This package provides LabKey's base JS ESLint configuration (without React plugins) as an extensible shared config.

## Installing

```bash
$ npm install --save-dev --save-exact @labkey/eslint-config-base
```

You'll need to also install all of the dependencies.  On OSX or Linux, you can use this snippet to install all of the dependencies:

```bash
$ npm info @labkey/eslint-config-base peerDependencies --json | command sed 's/[\{\},]//g ; s/: /@/g' | xargs npm install --save-dev --save-exact --dry-run
```

When you have inspected the output, you can remove the `--dy-run` flag to actually perform the install.


## Usage

Create an .eslintrc.json file with the following contents

```jsonp
{
  "extends": "@labkey/eslint-config-base"
}
```



