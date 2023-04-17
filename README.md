# Module-20-Challange---Solidity

#### JointSavings Smart Contract
This is a Solidity smart contract that implements a joint savings account, where two authorized Ethereum addresses can deposit and withdraw funds.

#### Getting Started
To get started with this project, you will need an Ethereum wallet and an IDE like Remix to deploy and test the smart contract.

##### Prerequisites
- An Ethereum wallet like MetaMask
- The Remix IDE for Solidity development
##### Installing
- Clone the repository to your local machine.
- Open the JointSavings.sol file in the Remix IDE.
- Compile the smart contract using the Solidity compiler.
- Deploy the contract to the Ethereum network using the Remix IDE.
#### How to Use
The smart contract has the following functions that you can use:

##### setAccounts
This function sets the two authorized Ethereum addresses that can withdraw funds from the contract. You need to call this function before you can deposit or withdraw any funds.
![Set_Account ](https://user-images.githubusercontent.com/116679505/232491076-24354aed-04c2-4c2d-b78e-7e484846bc45.png)

##### deposit
This function allows you to deposit funds into the contract. You need to send Ether to this function to deposit funds.

![Transfer_1Eather](https://user-images.githubusercontent.com/116679505/232491511-78af892b-ca61-404d-b4f0-7fd3f8ab6e6f.png)

![Transfer_5Eather](https://user-images.githubusercontent.com/116679505/232491219-593afc09-cba5-4334-90f5-51a7607c0c2e.png)

![Transfer_10Eather](https://user-images.githubusercontent.com/116679505/232491263-e0cb87e2-f5f6-4f6b-bb55-0c01596bc539.png)


##### withdraw
This function allows you to withdraw funds from the contract. You need to specify the amount to withdraw and the recipient address.
![Withdrawl_5Eather](https://user-images.githubusercontent.com/116679505/232491586-b439cb56-eded-4a85-acf5-aa68949e8b9e.png)

![Withdrawl_10Eather](https://user-images.githubusercontent.com/116679505/232491603-d42558f6-d383-4943-a66b-a31a4d0dbb25.png)


##### contractBalance
This function returns the current balance of the contract.
##### lastToWithdraw
This function returns the address of the last person to withdraw funds from the contract.

![LastToWithdraw](https://user-images.githubusercontent.com/116679505/232492619-c67b517e-93ac-4285-868d-f5e4503921de.png)



##### lastWithdrawAmount
This function returns the amount of the last withdrawal from the contract.

![LastWithdraw](https://user-images.githubusercontent.com/116679505/232492647-2de82225-ab2b-4631-94fe-00900b3aeaf5.png)


#### Conclusion
In conclusion, this smart contract is a basic example of how Ethereum smart contracts work. It demonstrates the ability to send and receive Ether, restrict access to certain functions, and record important transaction data such as the address and amount of the last withdrawal.

This contract could be expanded upon and customized for specific use cases, such as creating a crowdfunding platform or a decentralized exchange. The possibilities are endless with Ethereum smart contracts, and they are changing the way we think about trust, transparency, and accountability in transactions.


