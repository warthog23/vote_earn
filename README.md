# Vote_Earn

Vote_Earn is a decentralized voting system built on the blockchain that rewards participants with tokens for casting their votes. This project aims to encourage engagement and fair participation in the voting process by providing incentives in the form of tokens.

## Features
- **Decentralized Voting**: Users can cast their votes on-chain without intermediaries.
- **Token Rewards**: Every user who votes receives a predefined amount of tokens.
- **Transparency**: The entire voting process is publicly recorded on the blockchain.
- **One Vote per Address**: Ensures fair participation by restricting each address to one vote.
- **Secure and Immutable**: Votes cannot be altered once cast.

## Deployed Contract
- **Contract Address**: `0xbe90B1f1D9B2E03b72244739aC3Af413a35C7Fcc`
- **Blockchain Network**: Edu Chain

## How It Works
1. Users interact with the contract to cast their vote.
2. The contract verifies if the user has already voted.
3. If eligible, the vote is recorded and the user receives reward tokens.
4. Votes and rewards can be queried on the blockchain.

## Usage
- Call the `vote()` function to cast your vote.
- Use `getTotalVotes()` to check the total number of votes.
- Use `getTokenBalance(address)` to see token rewards.

## License
This project is open-source and free to use under the MIT License.

