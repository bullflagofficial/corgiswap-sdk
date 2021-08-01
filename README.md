# Corgiswap SDK

Forked from the [Pancakeswap SDK](https://github.com/pancakeswap/pancake-swap-sdk/commit/7d81106174e16d1f1c6c91a93558736282a39ec1).

You can refer to the Pancakeswap SDK documentation [pancakeswap.finance](https://docs.pancakeswap.finance/get-started).

## Running tests

To run the tests, follow these steps. You must have at least node v10 and [yarn](https://yarnpkg.com/) installed.

First clone the repository:

```sh
git clone git@github.com:corgidoge-official/corgiswap-sdk.git
```

Move into the corgiswap-sdk working directory

```sh
cd corgiswap-sdk/
```

Install dependencies

```sh
yarn install
```

Run tests

```sh
yarn test
```

You should see output like the following:

```sh
yarn run v1.22.4
$ tsdx test
 PASS  test/constants.test.ts
 PASS  test/pair.test.ts
 PASS  test/fraction.test.ts
 PASS  test/miscellaneous.test.ts
 PASS  test/entities.test.ts
 PASS  test/trade.test.ts

Test Suites: 1 skipped, 6 passed, 6 of 7 total
Tests:       3 skipped, 82 passed, 85 total
Snapshots:   0 total
Time:        5.091s
Ran all test suites.
✨  Done in 6.61s.
```
