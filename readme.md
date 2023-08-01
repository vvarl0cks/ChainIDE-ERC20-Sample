# Create Your ERC-20 Token

ERC-20 has emerged as a technical standard used for all smart contracts on the Ethereum blockchain for token implementation.
Plenty of well-known digital currencies use the ERC-20 standard, including Maker (MKR), Augur (REP), Basic Attention Token (BAT), and OmiseGO (OMG).

### Prerequisite
To create your ERC-20 standard token, you need to install/Access:
1. [MetaMask](https://metamask.io/)
2. ChainIDE

If you don't know how to set up the development environment,
you can follow our guidelines to install MetaMask and create your projects by clicking
[here](https://chainide.gitbook.io/chainide-english-1/ethereum-ide-1/1.-ethereum-ide/untitled-1-1).

### What is ERC-20?
One of the most significant Ethereum tokens is known as [ERC-20](https://eips.ethereum.org/EIPS/eip-20). ERC-20 has emerged as the technical standard;
it is used for all smart contracts on the Ethereum blockchain for token implementation and provides a list of rules that all Ethereum-based tokens must follow.
ERC-20 is similar, in some respects, to bitcoin, Litecoin, and any other cryptocurrency;
ERC-20 tokens are blockchain-based assets that have value and can be sent and received.
The primary difference is that instead of running on their own blockchain, ERC-20 tokens are issued on the Ethereum network.
ERC stands for Ethereum Request for Comments. ERC20 defines six obligatory functions your smart contract should implement.

### Optional functions for ERC-20:
name

symbols

decimals

### Mandatory functions for the ERC-20 Token:
Total supply — the amount of tokens that exist at the moment

Balance of — shows the balance for the address

Transfer — sends a certain amount of tokens to the address

Transfer from — used for exchanging tokens among users who have these tokens

Approve — verifies that your the wallet address is eligible to send tokens to another user

Allowance — shows whether or not a user has a balance sufficient to send tokens to someone else

These 6 functions are recognized and identified by other smart contracts. In a nutshell, the
ERC20 token plays well with other smart contracts, and that’s why it is so popular.

### Extra Function for Airdrop:
An extra function with the name Airdrop has been included in the ERC-20 token that is used to get tokens every time you execute it;
a specific amount of tokens will be added to the owner's account and to the total supply.
Regarding Interface with .html extension. Don't forget to change the ABI code of the smart contract in the HTML file with your smart contract ABI code,
and change the contract address with the contract address that you will get after deploying your smart contract to the blockchain.
The ABI code can be gotten from the compile panel; after successful compilation, under the compile button, you can see an option for ABI and BYTE CODE;
you can copy the ABI code by clicking on the icon in front of the ABI.

![image-20221108173144183](https://d3gvnlbntpm4ho.cloudfront.net/ERC20_deployment_on_Goerli_Etherum/image-20221108173144183.png)

Once you have successfully compiled the smart contract, now you can deploy it to a blockchain. After the successful deployment,
a contract address will be assigned to a smart contract; by using the smart contract address and ABI code, you can interact with your smart contract.
The figures below show different methods to get information about the deployed smart contract.
1st Figure shows the contract information from the IDE output panel, and the 2nd figure shows the contract information through the "INTERACT" panel. 
You can use get contract information by following any of these methods.

![image-20221108173716727](https://d3gvnlbntpm4ho.cloudfront.net/ERC20_deployment_on_Goerli_Etherum/image-20221108173716727.png)

Once you have the contract address and the ABI, you can code using Web3, a combination of HTML, CSS, and JavaScript, to interact with your deployed smart contract.
We provide an example for you, but you need to change your ABI and address to your own ERC20 token.

![](https://d3gvnlbntpm4ho.cloudfront.net/ERC20_deployment_on_Goerli_Etherum/ERC_20_ABI_BYTECODE_CHANGE.png)

ChainIDE supports HTML, Solidity, Markdown, and all other file formats that are needed to create your dApps.
Once you click on the output view, you can see an interface according to your HTML file, and you can interact through this interface with your deployed smart contract.

![](https://d3gvnlbntpm4ho.cloudfront.net/ERC20_deployment_on_Goerli_Etherum/ERC_20_html_file_output.png)

As we can see, the output of the airdrop.html file.
In this file, we interact with ERC-20 standard token. An extra function for getting airdrop coins is added to the ERC-20 token, increasing the token (you'll get tokens) each time you execute your Get Airdrop function.


We hope this information helped you to create your ERC-20 token. If you have any questions, you can ask in our Forum at the link below.

Find us on following:
1. [Forum](https://forum.chainide.com/)

2. [Twitter](https://twitter.com/ChainIde)

3. [Telegram](https://t.me/joinchat/Q48BNwB-f8RlZTJl)

4. [Medium](https://medium.com/@matrixwhite-mgt)

5. [YouTube](https://www.youtube.com/channel/UCgvPUHayWfxAGiJCI2xOzNg)



