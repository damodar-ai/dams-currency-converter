
# Dams-currency-converter

This project is very useful for converting currencies of many countries of the world. Currency of one country into the value of currency of another country.


## Installation

Install my-project with npm

```bash
npm install dams-currency-converter
```
## How To Use
Add the type of package in package.json
```bash
"type":"module",

```
```bash
const freecurrencyapi = new Freecurrencyapi('Enter Your API Key Here');

```
```bash
import { convertCurrency } from "dams-currency-converter";
convertCurrency("USD" , "INR" ,100).then(res=>console.log(res));
```

    
## License

[Apache ](https://github.com/damodar-ai/dams-currency-converter/blob/main/LICENSE)


## Authors

- [@Damodar Tiwari](https://www.github.com/damodar-ai)


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![Apache License](https://img.shields.io/badge/License-Apache-green.svg)](https://github.com/damodar-ai/dams-currency-converter/blob/main/LICENSE)


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`API_KEY`

`ANOTHER_API_KEY`


## 🚀 About Me

I'm Damodar Tiwari a full stack developer...

