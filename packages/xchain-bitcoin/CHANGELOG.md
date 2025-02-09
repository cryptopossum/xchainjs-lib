# v.0.12.2 (2021-04-19)

- Export `calFee`

# v.0.12.1 (2021-03-02)

- Export `validateAddress`

# v.0.12.0 (2021-03-02)

### Breaking change

- replace `find`, `findIndex`
- Update @xchainjs/xchain-client package to 0.7.0
  
# v.0.11.1 (2021-02-26)

### Update

- Export `scanUTXOs` + `buildTx`

# v.0.11.0 (2021-02-24)

### Breaking change

- Update @xchainjs/xchain-client package to 0.6.0

# v.0.10.1 (2021-02-22)

### Update

- Uses BlockStream to submit transactions instead of Sochain

# v.0.10.0 (2021-02-19)

### Breaking change

- Update @xchainjs/xchain-client package to 0.5.0
- Make `feeRate` optional in `transfer()`, default is `fast`

### Update

- Update README.md

### Fix

- Fix `peerDependencies`

# v.0.9.0

### Breaking change

- Update @xchainjs/xchain-client package to 0.4.0
- Update @xchainjs/xchain-crypto package to 0.2.3
- Change `blockchair` to `sochain`
- Update `getSuggestedFee`

### Update

- Add `Service Providers` section in README.md

# v.0.8.2 (2021-01-30)

- Clear lib folder on build

# v.0.8.1 (2021-01-15)

### Change

- Export `getPrefix`

# v.0.8.0 (2021-01-15)

### Breaking change

- Move `getPrefix` to util

# v.0.7.1 (2021-01-12)

### Update

- Update `getBalance` to check api key #180
- Update comments for documentation

# v.0.7.0 (2020-12-28)

### Update

- Add `getDefaultFeesWithRates` to `utils` #157

### Breaking change

- Extract `getDefaultFees`, `calcFee` from `Client` to `utils` #157
- Remove `validateAddress` from `BitcoinClient`

# v.0.6.0 (2020-12-11)

### Update

- Update dependencies
- Add `getDefaultFees`
- Add `createTxInfo` to support transactions using Ledger
- Add `getDerivePath` helper

### Breaking changes

- Remove deprecated stuff of `electrs`
- Extract constants to `src/const`
- Extract common types to `types/common`

### Fix

- Update exports

# v.0.5.1 (2020-11-20)

### Update

- Use `getSeed` of `xchain-crypto`
- Remove `bip39` from dependencies
- Use latest `xchain-crypto@0.2.1`

# v.0.5.0 (2020-11-20)

### Breaking change

- Update @xchainjs/xchain-crypto package to 0.2.0, deprecating old keystores

# v.0.4.4 (2020-12-11)

### Fix:

- Use latest `xchain-client@0.1.0`

# v.0.4.3 (2020-11-11)

### Fix

- replaced functions properties to the arrow functions at the `Client`

# v.0.4.1 (2020-10-11)

### Fix:

- Use latest `xchain-client@0.0.7`

# v.0.4.0 (2020-09-11)

### Breaking changes:

- Remove usage of a phrase for `BIP39.mnemonicToSeedSync`
- Ignore transactions in `getTransactions` typed as 'nulldata' by Blockchair

# v.0.1.0 (2020-05-11)

First release
