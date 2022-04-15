# Paystack SDK

#### Why Another [Paystack](https://paystack.com) Package?

Other packages are either outdated or don't support types.

### Installation

For Yarn
`yarn add paystack-sdk`

For NPM
`npm install paystack-sdk`

### Usage

For Typescript

```
import {Paystack} from 'paystack-sdk';

const paystack = new Paystack("secret_key);
```

For Javscript

```
const Paystack = require('paystack-sdk').Paystack;
const paystack = new Paystack("secret_key");
```

All methods use promise meaning you can either use the `async...await` or `then...catch` or `try...catch`

### Available Functions

- Charge
- Customer
- Plan
- Product
- Subscription
- Transaction
- Transfer
- dedicated (For dedicated accounts)
