# Lesson 8 - HTML / Javascript Fund Me (Full stack / Front End)

## Notes and key learning points

1. HTML / Javascript
2. Later on will use Nextjs / Reactjs

- Metamask documentation https://docs.metamask.io/guide/mobile-best-practices.html

13:00 In `nodejs` use the `require()` function to import dependencies

- in front end Javascript can't use this - use the `import` key word instead
- `yarn add --dev prettier` - reformat code layout

13:10 Need the contract ABI and address

- Go back to the `hardhat-fund-me-fcc` folder
- `artifacts/contracts/FundMe.sol` then copy the `abi` array from `FundMe.json`

13:12 To get a contract address to interact with

- open new terminal window
- `cd ..` to move up to `hh-fcc` folder
- `cd hardhat-fund-me-fcc` to move into project folder
- `yarn hardhat node` to run localhost node and deploy FundMe contract
- in `constants.js` add in the address to the `contractAddress` variable

13:15 Importing a new account into Metamask

- use first account from the localhost node
- Set up Metamask to use localhost node (using url from node)
- Import account into Metamask and select Private Key - copy in

13:19 Resetting Metamask

- If get an RPC Error - 'Nonce too high'
- Usually if you close your hardhat node and then restart
- select the 'circle' to get menu, then settings
- Select 'Advanced' and then reset account

13:33 Reading from the blockchain - get balance functionality

13:35 Withdraw function
