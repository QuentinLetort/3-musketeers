# cash

> Get currency conversion.

![cash_picsou](https://media.giphy.com/media/xTiTnqUxyWbsAXq7Ju/giphy.gif)

## Installation
After changing directory to the current one, you can install the libraries by using the following command:
```sh
❯ npm install
```

## Usage

Launch:
```sh
❯ node bin/index.js
```
It will return the conversion rate from a default currency (USD) to others (USD, EUR, GBP, JPY by default).


#### Get the conversion rate for particular currencies

If you want to know the conversion rate from a currency to others (different from the default currencies), use the following command:
```sh
❯ node bin/index.js --set <FROM> <TO>
```
You just have to define the original currency and the desired currencies.

#### Get the currency conversion of a given value

If you want to know the conversion of a value from a currency to another, use the following command:
```sh
❯ node bin/index.js <amount> <FROM> <TO>
```
You just have to define the amount to convert, the original currency and the desired currencies.

#### Change the default currencies

If you want to change the default currencies, use the following command:
```sh
❯ node bin/index.js -s <FROM> <TO>
```
You just have to define the original currency and the desired currencies.

If you have any doubt about the commands, you can also find the information by using the help command:
```sh
❯ node bin/index.js --help
```



