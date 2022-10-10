+----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------+
| Name                             | Type                                                            | Slot | Offset | Bytes | Contract                                                                                                                  |
+========================================================================================================================================================================================================================================================+
| admin                            | address                                                         | 0    | 0      | 20    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| pendingAdmin                     | address                                                         | 1    | 0      | 20    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| comptrollerImplementation        | address                                                         | 2    | 0      | 20    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| pendingComptrollerImplementation | address                                                         | 3    | 0      | 20    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| oracle                           | contract PriceOracle                                            | 4    | 0      | 20    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| closeFactorMantissa              | uint256                                                         | 5    | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| liquidationIncentiveMantissa     | uint256                                                         | 6    | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| maxAssets                        | uint256                                                         | 7    | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| accountAssets                    | mapping(address => contract CToken[])                           | 8    | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| markets                          | mapping(address => struct ComptrollerV2Storage.Market)          | 9    | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| pauseGuardian                    | address                                                         | 10   | 0      | 20    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| _mintGuardianPaused              | bool                                                            | 10   | 20     | 1     | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| _borrowGuardianPaused            | bool                                                            | 10   | 21     | 1     | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| transferGuardianPaused           | bool                                                            | 10   | 22     | 1     | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| seizeGuardianPaused              | bool                                                            | 10   | 23     | 1     | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| mintGuardianPaused               | mapping(address => bool)                                        | 11   | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| borrowGuardianPaused             | mapping(address => bool)                                        | 12   | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| allMarkets                       | contract CToken[]                                               | 13   | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| compRate                         | uint256                                                         | 14   | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| compSpeeds                       | mapping(address => uint256)                                     | 15   | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| compSupplyState                  | mapping(address => struct ComptrollerV3Storage.CompMarketState) | 16   | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| compBorrowState                  | mapping(address => struct ComptrollerV3Storage.CompMarketState) | 17   | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| compSupplierIndex                | mapping(address => mapping(address => uint256))                 | 18   | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| compBorrowerIndex                | mapping(address => mapping(address => uint256))                 | 19   | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| compAccrued                      | mapping(address => uint256)                                     | 20   | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| borrowCapGuardian                | address                                                         | 21   | 0      | 20    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| borrowCaps                       | mapping(address => uint256)                                     | 22   | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| compContributorSpeeds            | mapping(address => uint256)                                     | 23   | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| lastContributorBlock             | mapping(address => uint256)                                     | 24   | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| compBorrowSpeeds                 | mapping(address => uint256)                                     | 25   | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| compSupplySpeeds                 | mapping(address => uint256)                                     | 26   | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| proposal65FixExecuted            | bool                                                            | 27   | 0      | 1     | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
|----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------|
| compReceivable                   | mapping(address => uint256)                                     | 28   | 0      | 32    | /Users/leekt/workspace/cicada/database/ethereum/mainnet/3d/3d9819210a31b4961b30ef54be2aed79b9c9cd3b/logic.sol:Comptroller |
+----------------------------------+-----------------------------------------------------------------+------+--------+-------+---------------------------------------------------------------------------------------------------------------------------+