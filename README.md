# Contract
This contract has two functions:

1.set(uint256 x): This function takes an input x and sets the storedData variable to that value.

get(): This function returns the current value of storedData.

# HTML

HTML Structure:

1.This is a simple HTML file containing the structure of a web page.

2.It includes input fields, buttons, and a paragraph element (<p>) to display the stored value from the smart contract.

JavaScript:

The JavaScript code is responsible for interacting with the Ethereum blockchain and the deployed smart contract.

Web3.js:

1.The code uses Web3.js, a JavaScript library for interacting with Ethereum.
2.It includes the Web3.js library from a CDN (Content Delivery Network) using the <script> tag.

setValue() Function:

1.This function is called when the user clicks the "Set Value" button.

2.It retrieves the input value from the HTML input field.

3.It requests access to the user's Ethereum accounts using MetaMask.

4.It specifies the contract address and ABI (Application Binary Interface).

5.It creates a new Web3 instance connected to the user's Ethereum provider (MetaMask).

6.It instantiates a contract object using the contract ABI and address.

7.It calls the set() function of the contract, passing the input value.

8.After the transaction is confirmed, it displays an alert indicating success.

getValue() Function:

1.This function is called when the user clicks the "Get Value" button.

2.It specifies the contract address and ABI (Application Binary Interface).

3.It creates a new Web3 instance connected to the user's Ethereum provider (MetaMask).

4.It instantiates a contract object using the contract ABI and address.

5.It calls the get() function of the contract to retrieve the stored value.

6.It updates the HTML paragraph element (<p>) to display the retrieved value.
