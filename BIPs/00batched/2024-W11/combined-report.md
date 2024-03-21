
## Mainnet DAO Multisig
[Tenderly](https://dashboard.tenderly.co/public/safe/safe-apps/simulator/4722dbba-b150-4869-af11-5fc71e1b29c7)

[Sign Nonce 239](https://app.safe.global/transactions/queue?safe=eth:0x10A19e7eE7d7F8a52822f6817de8ea18204F2e4f)
```
+------------+-------------------------------------------------+-----------------------------------------------------------------------------+----------------------------+---------+------------+
| function   | token_symbol                                    | recipient                                                                   | amount                     | bip     |   tx_index |
+============+=================================================+=============================================================================+============================+=========+============+
| transfer   | USDC:0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48 | multisigs/beets_service_provider:0x811912c19eEF91b9Dc3cA52fc426590cFB84FC86 | 29000.0 (RAW: 29000000000) | BIP-518 |          3 |
+------------+-------------------------------------------------+-----------------------------------------------------------------------------+----------------------------+---------+------------+
| transfer   | USDC:0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48 | multisigs/beets_service_provider:0x811912c19eEF91b9Dc3cA52fc426590cFB84FC86 | 30000.0 (RAW: 30000000000) | BIP-519 |          4 |
+------------+-------------------------------------------------+-----------------------------------------------------------------------------+----------------------------+---------+------------+
```
```
+---------------------+-----------------------------------------------------------------+----------------------+-------------------+--------------+------------+
| fx_name             | to                                                              |                value | inputs            | bip_number   | tx_index   |
+=====================+=================================================================+======================+===================+==============+============+
| processExpiredLocks | 0x3Fa73f1E5d8A792C80F426fc8F84FBF7Ce9bBCAC (aura/vlAURA)        |                    0 | {                 | BIP-551      | N/A        |
|                     |                                                                 |                      |   "_relock": true |              |            |
|                     |                                                                 |                      | }                 |              |            |
+---------------------+-----------------------------------------------------------------+----------------------+-------------------+--------------+------------+
| claim               | 0xFd72170339AC6d7bdda09D1eACA346B21a30D422 (Not Found)          |                    0 | {                 | BIP-551      | N/A        |
|                     |                                                                 |                      |   "_lock": true   |              |            |
|                     |                                                                 |                      | }                 |              |            |
+---------------------+-----------------------------------------------------------------+----------------------+-------------------+--------------+------------+
| !!N/A!!             | 0x166f54F44F271407f24AA1BE415a730035637325 (multisigs/maxi_ops) | 50000000000000000000 | "N/A"             | BIP-556      | N/A        |
+---------------------+-----------------------------------------------------------------+----------------------+-------------------+--------------+------------+
```