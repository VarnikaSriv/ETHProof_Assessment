PROJECT TITLE: ETH PROOF PROJECT TO CREATE TOKENS AND CHECK THE BALANCE AND TOTAL SUPPLY FOR THE ACCOUNT
The project is about making a contract to create tokens and providing values to that token. The program logic further checks for the account's balance and total supply of tokens. 

DESCRIPTION:
The code of this project builds a contract and aims at creating tokens. Firstly, the public state variables are created to declare the Token name, Token abbreviation and Total supply. The value of these three variables
are initialised. Then a mapping is declared from address to uint as (address => uint). I've named it as balances in the code and declared it as public. The address maps to uint, which means unsigned integer because the
balance will be returned in uint type. Further on, fucntion mint is created whihc takes two values as its parameter, address and value. The address for the account and the value for the value we provide for the token. 
This function will increment the account balance and the total supply with the value we will provide to the token. This will return the total supply as well as the account balance afater we transact our mint function
with the value of the token. Next up is the defintion of the function burn which implements the logic for doing work exactly the opposite of the mint function. The burn function destroys the tokens. Same as the mint 
function, it also takes two parameter values, being address and value. The address takes the account address and the value takes the provided value for the token. It detroys the amount of tokens from the main balance
and totoal supply as much as we provide while we transact this function. After compilation, we will deploy our code. Then in the functions, we will input the values. We'll need to copy an account address to the mint 
and burn functions and also to the balance variable. These will then return the values of the total supply and the account balance.

EXECUTING PROGRAM
To run this program, I've used Remix, an online Solidity IDE. 
We need to add the License as well as the Solidity version that we are using in the code. We can compile our code by clicking on the solidity compiler and clicking on the "Compile FinalETHProject.sol". This will
compile our code. Then we can deploy our code on the deploy and run transactions section. We can deploy and then click on the contract name as it displays below. We can then input values and run our functions to obtain 
output. 

AUTHOR:
Varnika Srivastava

LICENSE:
This project is licensed under the MIT License as mentioned in the code.
