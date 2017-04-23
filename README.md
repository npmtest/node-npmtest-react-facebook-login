# npmtest-react-facebook-login

#### basic test coverage for  [react-facebook-login (v3.5.0)](https://github.com/keppelen/react-facebook-login)  [![npm package](https://img.shields.io/npm/v/npmtest-react-facebook-login.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-facebook-login) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-facebook-login.svg)](https://travis-ci.org/npmtest/node-npmtest-react-facebook-login)

#### A Component React for Facebook Login

[![NPM](https://nodei.co/npm/react-facebook-login.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-facebook-login)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-facebook-login/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-facebook-login/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-facebook-login/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-facebook-login/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-facebook-login/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-facebook-login/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-facebook-login/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-facebook-login/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-facebook-login/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-facebook-login/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-facebook-login/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-facebook-login/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-facebook-login/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-facebook-login/build/test-report.html](https://npmtest.github.io/node-npmtest-react-facebook-login/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-facebook-login/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-facebook-login/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-facebook-login/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-facebook-login/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-facebook-login/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-facebook-login/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-facebook-login/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-facebook-login/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Giovanni Keppelen"
    },
    "babel": {
        "presets": [
            "es2015",
            "react",
            "stage-0"
        ],
        "plugins": [
            "transform-object-assign"
        ]
    },
    "bugs": {
        "url": "https://github.com/keppelen/react-facebook-login/issues"
    },
    "dependencies": {},
    "description": "A Component React for Facebook Login",
    "devDependencies": {
        "autoprefixer": "^6.0.3",
        "babel": "^6.5.2",
        "babel-core": "^6.6.5",
        "babel-eslint": "^4.1.6",
        "babel-loader": "^6.2.4",
        "babel-plugin-transform-object-assign": "^6.22.0",
        "babel-preset-es2015": "^6.1.18",
        "babel-preset-react": "^6.1.18",
        "babel-preset-stage-0": "^6.5.0",
        "css-loader": "^0.19.0",
        "eslint": "^1.10.3",
        "eslint-config-airbnb": "^2.0.0",
        "eslint-plugin-react": "^3.11.3",
        "node-sass": "^3.3.x",
        "postcss-loader": "^0.6.0",
        "react": "^15.1.0",
        "react-addons-test-utils": "^15.1.0",
        "react-css-modules": "^3.5.0",
        "react-dom": "^15.1.0",
        "react-router": "^3.0.0",
        "sass-loader": "^3.0.0",
        "style-loader": "0.12.x",
        "webpack": "1.12.x",
        "webpack-dev-server": "1.12.x"
    },
    "directories": {},
    "dist": {
        "shasum": "6a3199e025bac814b2617fe3ae15f86799a402f8",
        "tarball": "https://registry.npmjs.org/react-facebook-login/-/react-facebook-login-3.5.0.tgz"
    },
    "gitHead": "24209e6a665c80b55a2fe59460113e65ed6e3501",
    "homepage": "https://github.com/keppelen/react-facebook-login",
    "keywords": [
        "react",
        "reactjs",
        "react-component",
        "facebook-login",
        "react-facebook-login"
    ],
    "license": "MIT",
    "main": "dist/facebook-login.js",
    "maintainers": [
        {
            "name": "keppelen"
        }
    ],
    "name": "react-facebook-login",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^15.1.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/keppelen/react-facebook-login.git"
    },
    "scripts": {
        "bundle": "NODE_ENV=production node_modules/.bin/webpack -p --config webpack.config.dist.js",
        "start": "NODE_ENV=development node_modules/.bin/webpack-dev-server --config webpack.config.js",
        "test": "eslint src/**/*.js"
    },
    "version": "3.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
