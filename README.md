# Project Title
CREATE A TOKEN

## Description
In this Project i have created a contract to fulfill the following requirements:
* Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
* Your contract will have a mapping of addresses to balances (address => uint)
* You will have a mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance of the address by that amount.
* Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the address.
* Lastly, your burn function should have conditionals to make sure the balance of account is greater than or equal to the amount that is supposed to be burned.

## Execution

* Firstly we will write our code in the Remix Ethereum IDE.
* Then we have to compile the file (myToken.sol in my case).
* Then we have to deploy our transaction in Deploy and Run Transactions Section.
* Then we have to copy the account address and paste it in the mint section below and then we have to enter the number of supplies we want in the value section under mint section.
* Then we have to transact the supplies and see the result.



