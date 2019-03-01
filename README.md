# ESLint Config Supercool

This is an eslint-config extension for rules that I think are most relevant to most FE applications.

# To enable this in ESLint configurations file (.eslintrc or .eslintrc.js or .eslintrc.json)

`module.exports` only required of you use `.eslintrc.js` file.

```json
module.exports = {
    // other options
    "extends": "eslint-config-supercool",
    // rest of the options
}
```

# Options that you get

You will get all the options present in the `"extends": "eslint:recommended"` extension.

The additional settings that I added are these:

```json
    "indent": ["warn","tab"],
    "quotes": ["warn","backtick"],
    "semi": ["error","always"],
    "no-extra-parens": 1,
    "no-template-curly-in-string": 1,
    "array-callback-return": 1,
    "block-scoped-var": 2,
    "class-methods-use-this": 1,
    "consistent-return": 2,
    "default-case": 1,
    "eqeqeq": 1,
    "no-alert": 2,
    "no-empty-function": 1,
    "no-eval": 2,
    "no-extend-native": 2,
    "no-extra-bind": 1,
    "no-invalid-this": 1,
    "no-lone-blocks": 1,
    "no-loop-func": 2,
    "no-magic-numbers": 1,
    "no-multi-spaces": 1,
    "no-multi-str": 2,
    "no-new": 1,
    "no-new-func": 2,
    "no-new-wrappers": 1,
    "no-param-reassign": 1,
    "no-proto": 2,
    "no-return-assign": 2,
    "no-self-compare": 1,
    "no-useless-return": 1,
    "no-with": 2,
    "vars-on-top": 1,
    "no-restricted-globals": ["error", "event", "fdescribe"],
    "no-shadow": 1,
    "no-shadow-restricted-names": 2,
    "no-undef-init": 1,
    "no-use-before-define": 1,
    "global-require": 1,
    "handle-callback-err": 1,
    "no-new-require": 1,
    "no-path-concat": 1,
    "array-bracket-spacing": 1,
    "capitalized-comments": 1,
    "comma-dangle": ["warn", "never"],
    "comma-spacing": 1,
    "comma-style": 1,
    "eol-last": 1,
    "func-names": ["warn", "as-needed"],
    "func-style": ["warn", "declaration", {
        "allowArrowFunctions": true
    }],
    "jsx-quotes": ["warn", "prefer-double"],
    "max-len": 1,
    "new-cap": ["error", { 
        "newIsCap": true,
        "capIsNew": false,
    }],
    "new-parens": 1,
    "no-array-constructor": 1,
    "no-lonely-if": 1,
    "no-multiple-empty-lines": 1,
    "no-new-object": 2,
    "no-plusplus": 1,
    "no-trailing-spaces": 1,
    "operator-assignment": 1,
    "space-before-function-paren": ["warn", "always"],
    "arrow-spacing": 1,
    "no-duplicate-imports": 2,
    "no-useless-constructor": 1,
    "no-var": 1,
    "object-shorthand": 1,
    "prefer-arrow-callback": 1,
    "prefer-const": 1,
    "prefer-destructuring": 1,
```

Hope you enjoy.

## Where to find me

My website is [knc.js.org](https://knc.js.org) 💻

I tweet at [@ItsKNC](https://twitter.com/@itsKNC) 🐦