# eslint-plugin-nns

a lint save you from 996

## Feature list

 * [x] 每天 18:00 之后禁止代码变更
 * [x] 周六周日 禁止代码变更

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-nns`:

```
$ npm install eslint-plugin-nns --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-nns` globally.

## Usage

Add `nns` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "nns"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "nns/no-illegal-working-time": "error"
    }
}
```

## Supported Rules

* Fill in provided rules here





