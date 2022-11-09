LEARNING SOLIDITY BUILDING A STORAGE WEB3 CONTRACT

Remix default workspace is present when:
i. Remix loads for the very first time 
ii. A new workspace is created with 'Default' template
iii. There are no files existing in the File Explorer

This workspace contains 3 directories:

1. 'contracts': Holds the contracts I will use for this project.
2. 'scripts': Contains four typescript files to deploy a contract. It is explained below.
3. 'tests': Where I will put the test for the different contracts.

SCRIPTS

The 'scripts' folder has four typescript files which help to deploy the 'Storage' contract using 'web3.js' and 'ethers.js' libraries.

For the deployment of any other contract, just update the contract's name from 'Storage' to the desired contract and provide constructor arguments accordingly 
in the file `deploy_with_ethers.ts` or  `deploy_with_web3.ts`

In the 'tests' folder there is a script containing Mocha-Chai unit tests for 'Storage' contract.

To run a script, right click on file name in the file explorer and click 'Run'. Remember, Solidity file must already be compiled.
Output from script will appear in terminal.
