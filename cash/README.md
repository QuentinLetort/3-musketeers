# cash

> Get currency conversion.

## Installation of librairies

```sh
❯ npm install
```

## Usage

Launch:
```sh
❯ node bin/index.js
```
It will return the conversion rate from a default currency (USD) to others (USD, EUR, GBP, JPY by default)

#### Get the conversion rate for particular currencies

If you want to know the conversion rate from a currency to others (different from the default currencies), use the following command:
```sh
❯ node bin/index.js --set <FROM> <TO>
```

#### Get the currency conversion of a given value

If you want to know the conversion of a value from a currency to another:
```sh
❯ node bin/index.js <amount> <FROM> <TO>
```

#### Change the default currencies

If you want to change the default currencies, use the following command:
```sh
❯ node bin/index.js -s <FROM> <TO>
```
In the three use case, you can define more than one destination currency




