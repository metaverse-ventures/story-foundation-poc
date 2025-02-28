# TypeScript SDK for IP Management  

### Get Started  

1. Install the dependencies:  

    ```  
    npm install  
    ```  

2. Rename the `.env.example` file to `.env`  

3. Read the docs below associated with the example you want to run  

## 📄 Run "Simple Mint and Register" Example  

1. Add your Testnet wallet's private key to `.env` file:  

    ```  
    WALLET_PRIVATE_KEY=<your_wallet_private_key>  
    ```  

2. Go to [Pinata](https://pinata.cloud/) and create a new API key. Add the JWT to your `.env` file:  

    ```  
    PINATA_JWT=<your_pinata_jwt>  
    ```  

3. Run the script:  

    ```  
    npm run mint-and-register  
    ```  

## 📄 Run "Simple Mint and Register SPG" Example  

1. Add your Testnet wallet's private key to `.env` file:  

    ```  
    WALLET_PRIVATE_KEY=<your_wallet_private_key>  
    ```  

2. Go to [Pinata](https://pinata.cloud/) and create a new API key. Add the JWT to your `.env` file:  

    ```  
    PINATA_JWT=<your_pinata_jwt>  
    ```  

3. [OPTIONAL] A public SPG NFT collection has been preconfigured (`0xc32A8a0FF3beDDDa58393d022aF433e78739FAbc`). If you want to create your own, run the command:  

    ```  
    npm run create-spg-collection  
    ```  

    - Copy the NFT contract address from the output and update your `.env` file:  

    ```  
    SPG_NFT_CONTRACT_ADDRESS=<your_spg_nft_contract_address>  
    ```  

4. Run the script:  

    ```  
    npm run mint-and-register-spg  
    ```  

## 🖼️ Run "Register Derivative Non-Commercial" Example  

1. Add your Testnet wallet's private key to `.env` file:  

    ```  
    WALLET_PRIVATE_KEY=<your_wallet_private_key>  
    ```  

2. Run the script:  

    ```  
    npm run register-deriv-non-com  
    ```  

## 💰 Run "Register Derivative Commercial" Example  

1. Add your Testnet wallet's private key to `.env` file:  

    ```  
    WALLET_PRIVATE_KEY=<your_wallet_private_key>  
    ```  

2. Ensure you have enough `$WIP` tokens before running the script. If not, the function will auto-wrap an equivalent amount of `$IP` into `$WIP`.  

3. Run the script:  

    ```  
    npm run register-deriv-com  
    ```  

## ⚡ Run "Register Derivative Commercial SPG" Example  

1. Add your Testnet wallet's private key to `.env` file:  

    ```  
    WALLET_PRIVATE_KEY=<your_wallet_private_key>  
    ```  

2. Ensure you have enough `$WIP` tokens before running the script.  

3. [OPTIONAL] If needed, create your own SPG NFT collection:  

    ```  
    npm run create-spg-collection  
    ```  

    - Copy the contract address and update your `.env` file:  

    ```  
    SPG_NFT_CONTRACT_ADDRESS=<your_spg_nft_contract_address>  
    ```  

4. Run the script:  

    ```  
    npm run register-deriv-com-spg  
    ```  

## ❌ Run "Dispute IP" Example  

1. Add your Testnet wallet's private key to `.env` file:  

    ```  
    WALLET_PRIVATE_KEY=<your_wallet_private_key>  
    ```  

2. Obtain a unique CID for dispute evidence (as duplicate CIDs are not allowed).  

3. Run the script:  

    ```  
    npm run dispute-ip  
    ```  
