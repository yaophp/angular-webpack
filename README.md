
# Angular-webpack
A clean and powerful init ENV(dev, test, prod) for you to start a new Angular project with webpack, which was from Angular offical recommended example (bug fixed)

* [En](https://angular.io/guide/webpack)
* [中文](https://angular.cn/docs/ts/latest/guide/webpack.html)


## Quick start
* Make sure you have installed Node(>= 6.0) and NPM (>= 3)


```bash
// first clone this git
git clone https://github.com/yaophp/angular-webpack.git yourProject

// then change directory to the yourProject
cd yourProject

// last install the repo with npm
npm install

```


## Commands && ENV
```bash

# development ------- when you start to build your project
npm run start

# production ------- webpack will build your project and output files to dist folder 
npm run build

# test ------------- for unit test
npm run test

```



## File Structure

```
yourProject/
 ├──config/                        * config source
 │   │
 │   ├──helpers.js                 * helper functions
 │   ├──karma-test-shim.js         * karma config for our unit tests
 │   ├──karma.conf.js              * karma config for our unit tests
 │   ├──webpack.common.js          * common webpack config
 │   ├──webpack.dev.js             * development webpack config
 │   ├──webpack.prod.js            * production webpack config
 │   └──webpack.test.js            * testing webpack config
 │
 ├──src/                           * app source
 │   │
 │   ├──main.ts                    * entry file for app, can be modified but shuld not be deleted
 │   ├──index.html                 * template for index, can be modified but shuld not be deleted
 │   ├──polyfills.ts               * polyfills file, can be modified but shuld not be deleted
 │   ├──vendor.ts                  * common vendor file, can be modified but shuld not be deleted
 │   │
 │   ├──app/                       * WebApp folder, orgnize it as you wish
 │   │   │
 │   │   ├──app.component.ts       * simple component 
 │   │   └──...                    * and so on.
 │   │
 │   ├──assets/                    * static source, orgnize it as you wish
 │   │   ├──images/                * imgages
 │   │   └──...                    * and so on.
 │   │
 │   └──...                        * add more files or folders as you wish
 │
 ├──tsconfig.json                  * typescript config
 ├──package-lock.json              * build by npm
 ├──package.json                   * dependencies
 ├──karma.js                       * karma config
 └──webpack.config.js              * webpack main configuration file

```

