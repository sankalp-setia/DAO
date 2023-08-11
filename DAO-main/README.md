# Decentralized Autonomous Organization (DAO)

For this [DAO](https://ethereum.org/en/dao/), a fake NFT marketplace has been created but pre-existing ones can also be used. The DAO allows the [BPH Token Holders](https://sepolia.etherscan.io/token/0x27357ef37b72726dbd6a15b9f5e9ba9729327fcd#balances) (DAO owners) to create and execute proposals to buy new NFTs while allowing everybody to view all the proposals created upto date. The owners may withdraw their share of tokens (eth) from the DAO whenever required.

The project can be viewed [here](https://dao-omega-teal.vercel.app/). <br />
The contract can be accessed [here](https://sepolia.etherscan.io/address/0x1a3f436b9b7d72463ffba8f52b6f7a10756ddbf4). <br />
The BPH Token can be viewed [here](https://sepolia.etherscan.io/token/0x27357ef37b72726dbd6a15b9f5e9ba9729327fcd). <br />
The fake NFT marketplace can be viewed [here](https://sepolia.etherscan.io/address/0x9a804737b230c06e4ee01e5e4eb9f23d52855832).

## More Details

The dApp has been deployed on Sepolia Testnet of Ethereum. The backend of the dApp has been created using [Hardhat](https://hardhat.org/) and is available in the [backend](https://github.com/Tanmay-Bhatnagar-03/DAO/tree/main/backend) directory. Smart contracts for the project are available in [backend/contracts](https://github.com/Tanmay-Bhatnagar-03/DAO/tree/main/backend/contracts) directory and it is written in [Solidity](https://soliditylang.org/). The deployment script for the smart contract is written in [JavaScript](https://developer.mozilla.org/en-US/docs/Web/javascript). <br />

The frontend of the website has been created by [Next.js](https://nextjs.org/) and deployed on [Vercel](https://vercel.com/). The website automatically sends a prompt to connect your wallet ([MetaMask](https://metamask.io/)) and you are then required to approve the request in the wallet.<br />

The DAO's treasury is created from the amount of eth locked-in through the [ICO](https://ico-two-henna.vercel.app/). This treasury empowers the DAO owners to execute a proposal. The DAO owners (token holders) can withdraw their eth at any point in time. The DAO is made such that the deadline to vote on proposals is set at 5 minutes from when the proposal was first created, after the deadline the proposals can be executed according to the majority vote.<br />

Click on `Create Proposal` button if you are a DAO owner willing to buy a new NFT for the DAO. Click on `View Proposals`, if you wish to see past proposals alongwith their execution status. Click on `Withdraw DAO ETH` button if are a DAO owner and wish to withdraw your share from the DAO.

## Features (Current and Upcoming)

- [x] The dApp connects to the wallet automatically and checks whether the user is a [BPH Token holder](https://sepolia.etherscan.io/token/0x27357ef37b72726dbd6a15b9f5e9ba9729327fcd#balances).
- [x] Only token holders can create and execute proposals for the DAO.
- [x] Project has been deployed on Sepolia and hence, users have to change their network to Sepolia before site can be accessed.
- [x] Members can vote `YAY!(Yes)` or `NAY!(No)` on each proposal.
- [x] Execution status of each proposal is visible on the dApp and execution is solely based on the result of vote taken.
- [ ] Verifying and publishing the contract on [Sepolia Blockchain Explorer](https://sepolia.etherscan.io/).

## Contribution

Feel free to contribute to this project to make it better!

## License

This project has an MIT License.

## Made by love

- [StarterTemplates](https://twitter.com/startertemp)
- [LearnWeb3DAO](https://learnweb3.io)
