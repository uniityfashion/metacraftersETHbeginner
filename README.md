# ETHassignment

# Project Title
create a token

# Description
User generating custom unique token.

# Getting Started

# Installing
Step 1: Access Remix IDE Open Remix IDE: Go to Remix IDE in your web browser. Remix is an online tool for developing smart contracts with Solidity.

Step 2: Writing the Solidity Code Create a New File:
In the Remix file explorer (left panel), click on the "+" button to create a new file. Name the file MyToken.sol. Write the Token Contract: Copy and paste the following Solidity code into MyToken.sol. This code uses the OpenZeppelin library for an ERC-20 token. Executing program How to run the program Step-by-step bullets code blocks for commands

Step 3: Compiling the Contract Select the Compiler Version: 
Go to the "Solidity Compiler" tab on the left panel. Ensure the compiler version is set to 0.8.0 or compatible with the pragma version in your contract. Click on the "Compile MyToken.sol" button. 

Step 4: Deploying the Contract Open the Deploy & Run Tab:
Go to the "Deploy & Run Transactions" tab on the left panel. Configure the Environment:
In the "Environment" dropdown, select "Injected Web3" if you want to deploy to a testnet or mainnet using MetaMask. Select "JavaScript VM" for a local, temporary blockchain instance for testing. Set the Initial Supply:

Under "Deploy", you will see a field to input constructor arguments. Enter the initial supply value (e.g., 0). Deploy the Contract:

Click the "Deploy" button. Confirm the transaction in MetaMask if you are using "Injected Web3". 

Step 5: Interacting with the Contract After deployment, you can interact with your contract directly in Remix:
Check Total Supply:
In the "Deployed Contracts" section, expand your deployed MyToken contract. Click on the totalSupply function to view the total supply of tokens. Check Balance:
Click on the balanceOf function. Enter an address (e.g., the deployer address) to check the token balance. 

Step 6: Modifications to Files/Folders No additional files or folders need to be modified when using Remix IDE. However, here are a few tips for further modifications:

Add More Functions: You can extend the contract with additional functions like burn, pause, etc. Use OpenZeppelin Contracts: Import other OpenZeppelin contracts for advanced functionality such as access control or token snapshots. Save and Export: Save your work frequently and export your contracts if needed by downloading the files from the Remix file explorer.
