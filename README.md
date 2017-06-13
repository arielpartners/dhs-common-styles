# dhs-common-styles
Common styles for DHS projects

## Prerequisites

* (Node)[http://www.nodejs.org] and (NPM)[http://www.npmjs.com] installed
* LESS compiling: Your project will need a build tool to compile LESS to CSS

## Installation

In the terminal, navigate to your project's root directory.  Run the following command:
```
npm install --save-dev https://github.com/arielpartners/dhs-common-styles.git
```
If successful, `dhs-common-styles` will be added to the `DevDependencies` section of `package.json`.  A new `dhs-common-styles` directory will be added to the `node_modules` directory.

## Usage

To import the complete set of styles, add the following to your project's main LESS stylesheet:
```
@import '../node_modules/dhs-common-styles/less/style';
```
Adjust path to `node_modules` directory as necessary.

Individual LESS files from dhs-common-styles can be selectively imported as well.  For example:

* Import variables: `@import '../node_modules/dhs-common-styles/less/_variable.less'`
* Import dropdown menu: `@import '../node_modules/dhs-common-styles/less/components/_dropdown_menu.less'`
