# ETH-AVAX-MODULE-3

# Introduction
The code in this repository comprises a Solidity smart contract that implements an ERC-20 token. The contract includes essential functionalities like token minting, burning, and transferring.
   #  -   Use the `mint` function to create the new tokens.
   # -    Use the `burn` function to destroy a certain amount of tokens.
  #  -    Use the `transfer` function to transfer the tokens to another address.

# Implementation
1. Clone the repository and install its dependencies:
 ```sh
git clone https://github.com/yashsharma8433/ETH-AVAX-MODULE-3.git

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
7. Select the file from the contracts directory "createandmint.sol".
8. Compile the contract in the Remix IDE.
9. In the deploy section of Remix, select the environment as "Dev-Hardhat Provider".
10. Deploy your contract on the local Hardhat network using the deploy button in Remix.
11. Confirm the deployment transaction in Remix.
12. Wait for the deployment transaction to be confirmed on the local Hardhat network.
13.  Once the contract is deployed, you will see the contract address in the Remix console.



## License
This project is licensed under the MIT License. See the [`LICENSE`](LICENSE) file for more information.
