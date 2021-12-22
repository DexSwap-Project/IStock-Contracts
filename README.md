# IStock Contract

```
git clone https://github.com/DexSwap-Project/IStock-Contracts.git
cd IStock-Contracts
yarn
yarn compile && yarn a1
```
deployment sample:
```
Starting migrations...
======================
> Network name:    'harmony_testnet'
> Network id:      1666700000
> Block gas limit: 80000000 (0x4c4b400)


1_initial_migration.js
======================

   Replacing 'Migrations'
   ----------------------
   > transaction hash:    0xa1b1677e86bdf1b5cb4eec229aa12e68ceb84ffe4b29c5a0f4c8938c47b62909
   > Blocks: 3            Seconds: 5
   > contract address:    0x5bd7ab9dC2e7e60670C207939f89895BCb476dE2
   > block number:        19185714
   > block timestamp:     1640199801
   > account:             0x71928387C8D507192C912B84A6eFbf603FBfEbAA
   > balance:             116.209741762706383862
   > gas used:            153706 (0x2586a)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00153706 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.00153706 ETH


2_deploy_contracts.js
=====================

   Replacing 'TokenFactory'
   ------------------------
   > transaction hash:    0x3f7b56a80945ae9105036e9a44a3e62857201160a822ba86100fb4debbfb2744
   > Blocks: 4            Seconds: 9
   > contract address:    0xF9405B07a1a2027905E3457726Ce45BEc9d8aC8B
   > block number:        19185728
   > block timestamp:     1640199829
   > account:             0x71928387C8D507192C912B84A6eFbf603FBfEbAA
   > balance:             116.188094242706383862
   > gas used:            2122497 (0x206301)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.02122497 ETH


   Replacing 'UST'
   ---------------
   > transaction hash:    0x29d4355bd1b24ace23a5df0c32d88ceff1a3aa025cae8b387122a84811a5ddad
   > Blocks: 4            Seconds: 9
   > contract address:    0x6cE8Bf2e6eee78E88B567c36B2Ac56f50e69eae3
   > block number:        19185736
   > block timestamp:     1640199845
   > account:             0x71928387C8D507192C912B84A6eFbf603FBfEbAA
   > balance:             116.180112282706383862
   > gas used:            798196 (0xc2df4)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00798196 ETH


   Replacing 'PriceFeeder'
   -----------------------
   > transaction hash:    0x91d1227b62be89b8ee65f13807b1e2da31fc30837262fb255e73a0ddb4c61335
   > Blocks: 4            Seconds: 9
   > contract address:    0x30aF8411f7Ae241B1bC67F996E2E364b342e9eb1
   > block number:        19185744
   > block timestamp:     1640199861
   > account:             0x71928387C8D507192C912B84A6eFbf603FBfEbAA
   > balance:             116.173787252706383862
   > gas used:            632503 (0x9a6b7)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00632503 ETH


   Replacing 'Perpetual'
   ---------------------
   > transaction hash:    0xee7880f70d5a71b28478767600cabc8372ff6acbc2ba24f6dbf78682f52ca4fd
   > Blocks: 4            Seconds: 9
   > contract address:    0x6D4DF5742861066555AA02261B1c2D3527ed36E0
   > block number:        19185752
   > block timestamp:     1640199877
   > account:             0x71928387C8D507192C912B84A6eFbf603FBfEbAA
   > balance:             116.138094962706383862
   > gas used:            3569229 (0x36764d)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.03569229 ETH


   Replacing 'AMM'
   ---------------
   > transaction hash:    0x8a83b6fecd2f4bd5e7b6900df5ae41aece6633d3255ce9093a5bff3549c1710d
   > Blocks: 4            Seconds: 9
   > contract address:    0x72Ca0cc446FE11827CEd5Df94689439814E0B17b
   > block number:        19185761
   > block timestamp:     1640199895
   > account:             0x71928387C8D507192C912B84A6eFbf603FBfEbAA
   > balance:             116.085541772706383862
   > gas used:            5255319 (0x503097)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.05255319 ETH


   Replacing 'FundingCalculator'
   -----------------------------
   > transaction hash:    0x65e150271be02e3be704bf53bd95e1c2522bdae2c12b335d662ab6dc938dce5b
   > Blocks: 5            Seconds: 9
   > contract address:    0x6f6d7013FF7A463d794c8a39CA4Bf61Ea33E5AE3
   > block number:        19185769
   > block timestamp:     1640199911
   > account:             0x71928387C8D507192C912B84A6eFbf603FBfEbAA
   > balance:             116.065718152706383862
   > gas used:            1982362 (0x1e3f9a)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.01982362 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.14360106 ETH


3_setup_initial_values.js
=========================

   > Saving migration to chain.
   -------------------------------------
   > Total cost:                   0 ETH


Summary
=======
> Total deployments:   7
> Final cost:          0.14513812 ETH


Done in 242.01s.
```
