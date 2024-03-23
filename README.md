## FileCorgi Contract Address

FileCorgi Token (CORGI) is a custom ERC20 token deployed on the Ethereum blockchain. The token contract includes functionality for transferring tokens, managing allowances, and implementing token fees and burns. Below are some key features of the CORGI token:

- **Name:** FileCorgi Token
- **Symbol:** CORGI
- **Decimals:** 18
- **Total Supply:** Dynamic (minted initially with a specific amount)
- **Transaction Fee:** Customizable, a percentage of each transaction can be set as a fee
- **Burn Fee:** Customizable, a percentage of each transaction can be burned
- **Fee Address:** The address where the transaction and burn fees are sent

### Contract Features

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
- Name: FileCorgi Token
- Symbol: CORGI
- Decimals: 18
- Initial Balance: Customizable, minted initially to the contract owner
- Fee Receiver: Customizable, the address where the initial Ether value is sent during deployment

### Usage
- The contract owner can update the transaction fee, burn fee, and fee address.
- Token holders can transfer tokens to other addresses.
- The owner can recover ERC20 tokens sent into the contract.

For more information, please refer to the contract code and the Solidity documentation.
