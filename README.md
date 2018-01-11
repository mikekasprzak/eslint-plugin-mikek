# eslint-plugin-mikek

Mike K&#39;s eslint extras

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-mikek`:

```
$ npm install eslint-plugin-mikek --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-mikek` globally.

## Usage

Add `mikek` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "mikek"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "mikek/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here





