# METACRAFTERS-ETH-AVAX-MODULE-3

# Introduction
This repository contains the Solidity smart contract code for the ERC-20 token, designed with basic functionalities such as minting, burning, and transferring the tokens.
This README file provides an overview of the ERC-20 token contract that includes instructions on how to deploy the contract to the local Hardhat test network using Remix Connect Localhost and how to interact with it using Remix in the Hardhat provider network.

# Implementation
1. Clone the repository and install its dependencies:
 ```sh
git clone https://github.com/Palakkkkkkkkkk/METACRAFTERS-ETH-AVAX-MODULE-3.git

npm install
 ```
2. Install the `@remix-project/remixd` dependency to connect Remix IDE:

```sh
npm install -g @remix-project/remixd
```

3. Run the following command in the terminal to connect Remix IDE to the Hardhat local host:

```sh
remixd -s ./ --remix-ide https://remix.ethereum.org
```

4. Open a new terminal and start Hardhat's testing network:

```sh
npx hardhat node
```
5. Open the [Remix](https://remix.ethereum.org/) online IDE in your browser.
6. In the REMIX workspace, select "localhost" to connect to the local Hardhat network.
7. Select the file from the contracts directory "Lock.sol".
8. Compile the contract in the Remix IDE.
9. In the deploy section of Remix, select the environment as "Dev-Hardhat Provider".
10. Deploy your contract on the local Hardhat network using the deploy button in Remix.
11. Confirm the deployment transaction in Remix.
12. Wait for the deployment transaction to be confirmed on the local Hardhat network.
13.  Once the contract is deployed, you will see the contract address in the Remix console.

 # Interacting with the Contract using Remix with Hardhat Provider

After deploying the RUK token contract to the local Hardhat test network, you can interact with the contract using Remix with Hardhat provider. Here are the steps to get started:

1. Open the [Remix](https://remix.ethereum.org/) online IDE in your browser.

2. In the "File Explorer" section, locate the `Token.sol` file and open it.

3. In the "Deployed Contracts" section, click on the contract named `Token`.

4. In the "At Address" input field, enter the contract address obtained during deployment.

5. Click the "At Address" button to load the contract instance.

6. You can now interact with the RUK token contract through the provided functions.

   - Use the `balanceOf` function to check the token balance of a specific address.
   - Use the `transfer` function to send RUK tokens from your address to another address.
   - Use the `mint` function (accessible only to the contract owner) to mint

 new RUK tokens.
   - Use the `burn` function to burn a specific amount of your RUK tokens.

7. Set the required parameters for each function and click the corresponding button to execute the transaction.

8. Confirm the transaction details and sign the transaction in Remix.

9. Wait for the transaction to be confirmed on the local Hardhat network.

10. You can view the transaction status and emitted events in the Remix console.

## Author
PALAK JAIN :)

## License
This project is licensed under the MIT License. See the [`LICENSE`](LICENSE) file for more information.
