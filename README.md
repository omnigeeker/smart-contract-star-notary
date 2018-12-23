# smart-contract-star-notary

How to use it

#### install truffle-hdwallet-provider

```
npm install --save truffle-hdwallet-provider 
```

#### 

```
truffle develop
```

#### Compile solidity files:

```
truffle(develop)> compile
```

#### Test all testcases

```
truffle(develop)> test
```

#### Deploy to ethereum network `Rinkeby`:

```
truffle(develop)> migrate --reset --network rinkeby
```

#### Then

```
Running migration: 1_initial_migration.js
  Replacing Migrations...
  ... 0x3da49131f8203dfceb6e37cdf7670160d83776d6a40c64750c192296cb535430
  Migrations: 0x9d91596af813be2a4ae353632b31ac85520fb3d7
Saving successful migration to network...
  ... 0x1884168dbbb7e8fba1400b8f6126de8f3a1f94522c9191288bc8db3a4da012e4
Saving artifacts...
Running migration: 2_deploy_starnotary.js
  Replacing StarNotary...
  ... 0x978a5ac1f7e7d3bb3ec573949c3db43967de0e24b6132114f3a70bfa4c19507d
  StarNotary: 0x923696983205e51ddc3197d58b7caf98eec6f1c3
Saving successful migration to network...
  ... 0x124da6a78dd3ee68ed24e8a4a2eb4d3919cf9b4c983d84744445ca2d92320c68
Saving artifacts...
```

#### Contract

Contract address:

[0x923696983205e51ddc3197d58b7caf98eec6f1c3](https://rinkeby.etherscan.io/address/0x923696983205e51ddc3197d58b7caf98eec6f1c3)

Contract Hash:
[0x978a5ac1f7e7d3bb3ec573949c3db43967de0e24b6132114f3a70bfa4c19507d]
(https://rinkeby.etherscan.io/tx/0x978a5ac1f7e7d3bb3ec573949c3db43967de0e24b6132114f3a70bfa4c19507d)
