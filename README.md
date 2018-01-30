# ngclirc
angular cli rc

## Configuration
1. change packageManager from `npm` to `yarn`
2. change default style ext from `css` to `scss`

# Usage
## Step 1. Install ngclirc
```bash
npm i -D ngclirc
```

## Step 2. Add `.angular-cli.json` in your home `~` path
```bash
cp .angular-cli.json ~/.angular-cli.json
```

## Rules
```js
{
  "defaults": {
    // 默认使用scss编译
    "styleExt": "scss"
  },
  // 使用yarn代替npm
  "packageManager": "yarn"
}
```
