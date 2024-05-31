##  Epic Captures Token on Avalanche Subnet

I have created a token called - Epic Captures which is my Photography name . This token is based on ERC20 so it implements ERC20 functions and there's also another contract called Vault which is deployed to our local subnet.

## Description

The Epic Capture is able to implement ERC20 functions like :
- mint - to add Epic Capture token to the sender's address
- burn - to deduct Epic Capture tokens from the sender's address
- transfer - to transfer Epic Capture tokens from the sender to the receiver's address
- approve - to approve the spender to be able to spend Epic Capture tokens.

In the Vault , we are able to :
- deposit : add a certain number of shares to toal supply and balance.
- withdraw: deduct a certain number of shares from the total supply and the balance.


## Getting Started
 
### Subnet Creation
 
1. Either use a MAC terminal or Linux terminal
2. Install the Avalanche CLI
3. Export the path
4. `avalanche subnet create mySubnet`
5. `avalanche subnet deploy mySubnet`

## Executing Code

- Head to [remix.ethereum.org] and paste the code 
- Either create two different solidty files OR
- Paste both in the same file
- Choose the contract you want to deploy in contracts and deploy individually.
- Approve the Vault contract address to be able to transact a specified amount.
- Interact with both the contracts.

## Authors
 
Name - Shamanth Shashi
 
mail - [shamanthshashi2@gmail.com]
 
## License
 
This project is licensed under the MIT License - see the LICENSE.md file for details
 
 
