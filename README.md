# validity - Validation framework

[![NPM Details](https://nodei.co/npm/validity.png?stars&downloads)](https://npmjs.org/package/validity)

[![build status](https://api.travis-ci.org/serby/validity.png)](http://travis-ci.org/serby/validity)

An extendible validation framework for validating the properties of an object. Also contains a number of standard validators.

## Installation

    npm install validity

## Run Tests

    npm test

## Validators

Validity comes with some very basic example validators (required, email, integer, length and a few others). No more validators
will be added to this repo (in fact some of the more obscure ones may be removed in future). They should be built as individual
npm modules (with their own tests) so that applications can pick and choose which they use. Validators should be added to npm
repo with the `validity-` prefix so that people can find them with a quick [npm search](https://npmjs.org/search?q=validity-)
(or via the cli: `npm search validity-`).

The are a few validators that currently exist and can be used for reference:

- [validity-alphanumeric-property](https://www.npmjs.com/package/validity-alphanumeric-property)
- [validity-date-before-property](https://www.npmjs.com/package/validity-date-before-property)
- [validity-date-in-range](https://www.npmjs.com/package/validity-date-in-range)
- [validity-entity-exists](https://www.npmjs.com/package/validity-entity-exists)
- [validity-equal](https://www.npmjs.com/package/validity-equal)
- [validity-equal-field](https://www.npmjs.com/package/validity-equal-field)
- [validity-float](https://www.npmjs.com/package/validity-float)
- [validity-number](https://www.npmjs.com/package/validity-number)
- [validity-number-in-range](https://www.npmjs.com/package/validity-number-in-range)
- [validity-payment-card-number](https://www.npmjs.com/package/validity-payment-card-number)
- [validity-regex-match](https://www.npmjs.com/package/validity-regex-match)
- [validity-require-one](https://www.npmjs.com/package/validity-require-one)
- [validity-required-options](https://www.npmjs.com/package/validity-required-options)
- [validity-string-represents-mongodb-objectid](https://www.npmjs.com/package/validity-string-represents-mongodb-objectid)
- [validity-unique-property](https://www.npmjs.com/package/validity-unique-property)
- [validity-url-optional-tlds](https://www.npmjs.com/package/validity-url-optional-tlds)
- [validity-validate-each](https://www.npmjs.com/package/validity-validate-each)
- [validity-validate-if-property-equals](https://www.npmjs.com/package/validity-validate-if-property-equals)
- [validity-validate-if-property-set](https://www.npmjs.com/package/validity-validate-if-property-set)
- [validity-validate-if-set](https://www.npmjs.com/package/validity-validate-if-set)

## Credits
[Paul Serby](https://github.com/serby/) follow me on twitter [@serby](http://twitter.com/serby)

## Licence
Licenced under the [New BSD License](http://opensource.org/licenses/bsd-license.php)
