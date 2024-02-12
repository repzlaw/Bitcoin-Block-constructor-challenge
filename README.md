# Bitcoin Block constructor challenge

## Description

Built a bitcoin block constructor using typescript.

## Problem Description

Bitcoin miners construct blocks by selecting a set of transactions from their mempool. Each transaction in the mempool:

- Includes a fee, which is collected by the miner if that transaction is included in a block.
- Has a weight, indicating the size of the transaction.
- May have one or more parent transactions, which are also in the mempool.

The miner selects an ordered list of transactions with a combined weight below the maximum block weight. Transactions with parent transactions in the mempool may be included in the list, but only if all of their parents appear before them in the list.


### Requirements

-   [Node.js](https://nodejs.org/en/) v20.0.0 or higher
-   [NPM](https://www.npmjs.com/) v9.0.0 or higher

#### Installation

```bash
$ npm install
```

#### Running the app in development mode

```bash
$ npm run dev
```

#### Build the app

```bash
$ npm run build
```

#### Running the app

```bash
$ npm run start
```

#### Test

```bash
$ npm test
```

