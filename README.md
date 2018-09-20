# es6-nodejs-project-kickstart

[![Build Status][travis-image]][travis-url]
[![codecov][codecov-image]][codecov-url]
[![MIT License][license-image]][license-url]


## Tools Used 

- [babel-cli](https://babeljs.io/)
- [mocha](https://mochajs.org)
- [chai](https://github.com/chaijs/chai)
- [chai-http](https://www.chaijs.com/plugins/chai-http)
- [eslint](https://github.com/eslint/eslint)
- [eslint-config-airbnb](https://www.npmjs.com/package/eslint-config-airbnb)
- [eslint-plugin-import](https://www.npmjs.com/package/eslint-plugin-import)
- [nyc](https://github.com/istanbuljs/nyc)

# Quick Start

1. Make sure you have recent, stable version of nodejs in your system. Please check version before run
```
$  node -v
```
2. Clone or download this repository.

3. Run this following command in your terminal from the project folder

```shell
$ npm install
```

# List of Commands/Tasks

### Lint
#### Perform eslint in your project 
```shell
$ npm run lint
```

### Lint Fix
#### Most of the errors reported by eslint fixed by using this command 
```shell
$ npm run lint-fix
```

### Test
#### This will run all test cases 
```shell
$ node test 
```

### Generate nyc report -- (optional command)
#### After testcases passed this will generate nyc report and uploads to codecov 
```shell
$ node report-coverage 
```

### Build (Transpiled)
#### This will create '/dist' folder and converts the ES6 code into es5   
```shell
$ node run build
```

### Start nodejs server
```shell
$ node start
```






[codecov-url]:https://codecov.io/gh/srinivasKandukuri/es6-nodejs-project-kickstart
[codecov-image]: https://codecov.io/gh/srinivasKandukuri/es6-nodejs-project-kickstart/branch/master/graph/badge.svg

[travis-url]:https://travis-ci.org/srinivasKandukuri/es6-nodejs-project-kickstart
[travis-image]: https://travis-ci.org/srinivasKandukuri/es6-nodejs-project-kickstart.svg?branch=master

[license-url]: https://github.com/srinivasKandukuri/es6-nodejs-project-kickstart/blob/master/LICENSE
[license-image]: http://img.shields.io/badge/license-MIT-000000.svg?style=flat-square
