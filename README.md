# eslint-config-prettier-ts

> node module which lints TypeScript projects according to recommended rules vis eslint and prettier.


## Usage

In the project you wish to lint

**.eslintrc**
```
{
    "extends": "eslint-config-prettier-ts"
}
```

**prettier.config.js**
```
module.exports = require('eslint-config-prettier-ts/.prettierrc');
```

**package.json**

```
  "scripts": {
    "lint": "eslint ./"
  },
```

## Install

```
git clone https://github.com/michaelmelody91/eslint-config-prettier-ts
cd eslint-config-prettier-ts
yarn link
cd <PROJECT_TO_LINT>
yarn link eslint-config-prettier-ts
```

## Acknowledgments

[Medium: How to create your own shared eslint prettier and stylelint configuration](https://natterstefan.medium.com/how-to-create-your-own-shared-eslint-prettier-and-stylelint-configuration-3930dd764de3)

[Using eslint and prettier in a typescript project](https://www.robertcooper.me/using-eslint-and-prettier-in-a-typescript-project)

## License

MIT

