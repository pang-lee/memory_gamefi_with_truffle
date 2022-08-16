# memory_gamefi_with_truffle

It is a blockchain game which made by truffle framework  
And the whole asset is follow the course of https://www.youtube.com/watch?v=x-6ruqmNS3o&t=4696s  
It youtube have a lot of DAPP tutorial.  
If you want to build awesome DAPP remember to follow this channel https://www.youtube.com/c/DappUniversity  

Here is som e snapshot of this application  

![未命名](https://user-images.githubusercontent.com/13313753/184829651-7d8e81fd-ee87-40ef-badd-43ab996c6b30.png)


![未命名2](https://user-images.githubusercontent.com/13313753/184829652-e49d1f4c-0e29-4fed-90cf-df437053a009.png)

#####The develop process of this applictaion  
If you want to run this application, you need to download and install Ganache and node first  
After you download you need to run truffle migrate --reset to reset the whole smart contract  
And run npm run start to start react application  
Inside the src/components/App.js define the web3.js to connect with metamsk  
And the main of the game is inside the component folder including flip card and store card logic  
And if you need to use the smart contract functionality you have to include the ABI from solidity output  

And inside the contract/memorytoeken.sol defined the most of the NFT mining logic  
It inherit the ERC721 standard for NFT mining  
In the memorytoken.sol of _mint function is coming from ERC721 code with modification  
