# Smart Contract   

This repository is designed to help developers get started with building on top of Story. It includes a simple contract for IP registration of mock ERC-721 NFTs, along with accompanying tests.  

## Documentation  

Find the full smart contract guide here: https://docs.story.foundation/docs/get-started-with-the-smart-contracts

## Get Started  

1. Install dependencies: 
    ```  
    yarn  
    ```  

2. Run the tests:  

    - Run all tests:  

        ```  
        forge test --fork-url <your_rpc_url>  
        ```  

    - Run a specific test:  

        ```  
        forge test --fork-url <your_rpc_url> --match-path test/1_LicenseTerms.t.sol  
        ```  
