## [New Tool: Build a Flow SDK] - Milestone 1

## Description

This PR is for issue #20.

This version of the C++ SDK provides gRPC communication and a number of the SDK user stories, including script execution.

Usage documentation is available at https://github.com/Evan-Dapplica/FlowCppSDK

## Features:

Blocks:

- [x] retrieve a block by ID
- [x] retrieve a block by height
- [x] retrieve the latest block

Collections:

- [x] retrieve a collection by ID

Events:

- [x] retrieve events by name in the block height range

Scripts:

- [x] submit a script and parse the response
- [x] submit a script with arguments and parse the response

Accounts:

- [x] retrieve an account by address
- [ ] create a new account
- [ ] deploy a new contract to the account
- [ ] remove a contract from the account
- [ ] update an existing contract on the account

Transactions:

- [x] retrieve a transaction by ID
- [ ] sign a transaction (single payer, proposer, authorizer or combination of multiple)
- [ ] submit a signed transaction
- [ ] sign a transaction with arguments and submit it

## Milestones

- [x] 1: Implement the gRPC layer of the SDK, allowing communication with the Flow blockchain
- [ ] 2: Accomplish transaction signing in a way that handles the complex algorithm / hashing / encoding for the user.
- [ ] 3: Meet and exceed Flow SDK guidelines
- [ ] 4: Complete documentation and common usage examples are available