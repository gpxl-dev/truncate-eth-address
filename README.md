# truncate-eth-address

A very small and simple utility to truncate ethereum addresses to a more readable format. No dependencies.

Before: `0x7358B726830A2E222f9b139E90483A37142bcBE5`
After: `0x7358…cBE5`

#### Usage:

```javascript
import truncateEthAddress from 'truncate-eth-address'

const walletAddress = `0x7358B726830A2E222f9b139E90483A37142bcBE5`
console.log(`Your address is: ${truncateEthAddress(walletAddress)}`)
```
