# universal-validator
A string validation library for node

[![Build Status](https://travis-ci.org/iwannabebot/universal-validator.svg?branch=master)](https://travis-ci.org/iwannabebot/universal-validator)
[![Coverage Status](https://coveralls.io/repos/github/iwannabebot/universal-validator/badge.svg?branch=master)](https://coveralls.io/github/iwannabebot/universal-validator?branch=master)

## Installation 
```sh
npm install universal-validator --save
```
## Usage
### Javascript
```javascript
var validator = require('universal-validator');
console.log(validator.IsNullOrEmpty(' '));
```
```sh
Output should be true
```
### TypeScript
```typescript
import * as validator from 'universal-validator';
console.log(validator.IsNullOrEmpty('Goose'))
```
```sh
Output should be false
```