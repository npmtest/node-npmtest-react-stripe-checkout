# npmtest-react-stripe-checkout

#### basic test coverage for  [react-stripe-checkout (v2.2.5)](https://github.com/azmenak/react-stripe-checkout)  [![npm package](https://img.shields.io/npm/v/npmtest-react-stripe-checkout.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-stripe-checkout) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-stripe-checkout.svg)](https://travis-ci.org/npmtest/node-npmtest-react-stripe-checkout)

#### Easily inject checkout.js as a react component. Will load the script on demand and supports all the options from stripe docs.

[![NPM](https://nodei.co/npm/react-stripe-checkout.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-stripe-checkout)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-stripe-checkout/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-stripe-checkout/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-stripe-checkout/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-stripe-checkout/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-stripe-checkout/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-stripe-checkout/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-stripe-checkout/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-stripe-checkout/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-stripe-checkout/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-stripe-checkout/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-stripe-checkout/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-stripe-checkout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-stripe-checkout/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-stripe-checkout/build/test-report.html](https://npmtest.github.io/node-npmtest-react-stripe-checkout/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-stripe-checkout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-stripe-checkout/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-stripe-checkout/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-stripe-checkout/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-stripe-checkout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-stripe-checkout/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-stripe-checkout/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-stripe-checkout/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Adam Zmenak",
        "url": "http://azmenak.com"
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
        "url": "https://github.com/azmenak/react-stripe-checkout/issues"
    },
    "dependencies": {},
    "description": "Easily inject checkout.js as a react component. Will load the script on demand and supports all the options from stripe docs.",
    "devDependencies": {
        "babel-cli": "^6.11.4",
        "babel-core": "^6.11.4",
        "babel-eslint": "^6.1.2",
        "babel-plugin-transform-object-assign": "^6.8.0",
        "babel-preset-es2015": "^6.13.2",
        "babel-preset-react": "^6.11.1",
        "babel-preset-react-hmre": "^1.1.1",
        "babel-preset-stage-0": "^6.5.0",
        "babel-register": "^6.11.6",
        "enzyme": "^2.4.1",
        "eslint": "^2.10.1",
        "eslint-config-airbnb": "^9.0.1",
        "eslint-plugin-import": "^1.12.0",
        "eslint-plugin-jsx-a11y": "^1.2.0",
        "eslint-plugin-react": "^5.1.1",
        "expect": "^1.20.2",
        "jsdom": "^9.4.1",
        "mocha": "^3.0.1",
        "nyc": "^7.1.0",
        "react": "^15.3.0",
        "react-addons-test-utils": "^15.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1369fb44f522cfa21ba451d6be97d1a2b86ff84a",
        "tarball": "https://registry.npmjs.org/react-stripe-checkout/-/react-stripe-checkout-2.2.5.tgz"
    },
    "eslintConfig": {
        "parser": "babel-eslint",
        "extends": "airbnb",
        "env": {
            "browser": true,
            "node": true,
            "mocha": true,
            "es6": true
        },
        "plugins": [
            "react",
            "jsx-a11y"
        ],
        "parserOptions": {
            "ecmaVersion": 6,
            "sourceType": "module",
            "ecmaFeatures": {
                "jsx": true
            }
        },
        "globals": {
            "StripeCheckout": true
        },
        "rules": {
            "import/no-unresolved": 2,
            "comma-dangle": [
                2,
                "always-multiline"
            ],
            "indent": [
                2,
                2,
                {
                    "SwitchCase": 1
                }
            ],
            "no-console": 1,
            "max-len": 0,
            "prefer-template": 2,
            "no-use-before-define": 0,
            "newline-per-chained-call": 0,
            "arrow-body-style": [
                2,
                "as-needed"
            ],
            "jsx-a11y/href-no-hash": 2,
            "jsx-a11y/label-has-for": 2,
            "jsx-a11y/mouse-events-have-key-events": 2,
            "jsx-a11y/role-has-required-aria-props": 2,
            "jsx-a11y/role-supports-aria-props": 2,
            "jsx-a11y/aria-props": 2,
            "react/prop-types": [
                2,
                {
                    "ignore": [
                        "dispatch",
                        "children",
                        "className",
                        "style"
                    ]
                }
            ]
        }
    },
    "gitHead": "6acc1dd7aa8233e3421c4003878b7f8a3758fda5",
    "homepage": "https://github.com/azmenak/react-stripe-checkout",
    "keywords": [
        "react",
        "stripe",
        "checkout",
        "inject",
        "loaded",
        "easy"
    ],
    "license": "MIT",
    "main": "./dist/main.js",
    "maintainers": [
        {
            "name": "azmenak"
        }
    ],
    "name": "react-stripe-checkout",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/azmenak/react-stripe-checkout.git"
    },
    "scripts": {
        "build": "babel StripeCheckout.js --out-file ./dist/main.js",
        "cover": "nyc -x './spec.js' -n 'StripeCheckout.js' -r text -r html -r lcov npm test",
        "test": "mocha --require babel-register --require .test-setup.js -R spec ./spec.js",
        "version": "npm run build",
        "watch": "babel StripeCheckout.js --out-file ./dist/main.js --source-maps inline --watch"
    },
    "version": "2.2.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
