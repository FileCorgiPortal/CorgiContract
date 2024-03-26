## FileCorgi Contract Address

File Corgi (CORGI) is a custom ERC20 token deployed on the Filecoin blockchain. The token contract includes functionality for transferring tokens, managing allowances, and implementing token fees and burns. Below are some key features of the CORGI token:

- **Name:** FILE CORGI
- **Symbol:** CORGI
- **Decimals:** 9
- **Total Supply:** 1000000000000000000000000
- **Contract Address:** 0x10b97b19fabc54a95959aa462e5b37518399c080
- **Transaction Fee:** 1
- **Burn Fee:** 0
- **Fee Address:** 0x8b9D987ff510B3801c30D4F563D0deB68CA70262

#### SafeMath Library
- Provides safe arithmetic operations to prevent overflows and underflows.

#### ERC20 Implementation
- Implements the ERC20 standard functions for token transfers, allowances, and approvals.

#### Ownable Contract
- Implements basic access control, where an owner account has exclusive access to specific functions.

#### TokenRecover Contract
- Allows the owner to recover any ERC20 tokens sent into the contract.

### Deployment Details
The token contract was deployed with the following parameters:
- Name: File Corgi
- Symbol: CORGI
- Decimals: 9
- Initial Balance: Customizable, minted initially to the contract owner
- Fee Receiver: Customizable, the address where the initial Ether value is sent during deployment

### Usage
- The contract owner can update the transaction fee, burn fee, and fee address.
- Token holders can transfer tokens to other addresses.
- The owner can recover ERC20 tokens sent into the contract.

For more information, please refer to the contract code and the Solidity documentation.
