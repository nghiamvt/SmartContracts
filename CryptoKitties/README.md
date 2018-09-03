Crypto Kitties SmartContract
===

### Main Contract
```
contract KittyAccessControl
contract KittyBase is KittyAccessControl
contract KittyOwnership is KittyBase, ERC721
contract KittyBreeding is KittyOwnership
contract KittyAuction is KittyBreeding
contract KittyMinting is KittyAuction
contract KittyCore is KittyMinting
```
