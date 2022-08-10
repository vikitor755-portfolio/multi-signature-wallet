# multi-signature-wallet
A frontend that allows a user to deploy a smart contract that acts as a multi-signature wallet.

Notes:
This smart contract shall work only on the Polygon chain, which is EVM compatible so it might work on Ethereum maiinet, BSC and other chains, but is not guaranteed.

<h1>To do</h1>
Fronntend:
- Have user sign in with Metamask.
- See which contracts and which chains are associated with their wallet.
- Before deployment the deployer to set what percentage of the users need to vote for a decision to be approved.
- Have a button that allows them to deploy a multi-signature wallet contract.
- When a user has deployed a contract, allow them to go to a wallet menu.
- That wallet menu allows only the deployer to invite people.
- The deployer and all people need to approve a message/event before funds can be sent out.

<h1>Smart contart</h1>
- Public function that lists all assets held in the contract.
- Function only activateable by the owner that allows him/her to add users to the multi-sig consensus.
- Anyone can request a transaction or a transfer, everyone should be able to vote yes or no on each decision through the frontend before funds can be sent out from the contract.
- Users should be able to vote out a person off the multi-sig wallet. Make sure the voting off is done with safe math, especially if it is in percentages.

