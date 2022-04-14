# ZEN-20 Contract Development

A standard interface for fungible (interchangeable) tokens, like voting tokens, staking tokens or virtual currencies.

The following is a guide developing your own custom ZEN-20 token on the Zenith blockchain using the Remix IDE.&#x20;

**Prerequisites:**&#x20;

You must have Metamask installed already and have added Zenith to it. Click [here](../add-to-metamask/) if you haven't done that already.

Now click on network drop down and switch to either Zenith Mainnet or Zenith Testnet according to your requirements.&#x20;

![](<../.gitbook/assets/Screenshot 2022-03-30 at 1.32.24 PM.png>)

Click [here](https://remix.ethereum.org/#version=soljson-v0.8.7+commit.e28d00a7.js\&optimize=false\&runs=200\&gist=08d82670b94f2ebc7ea58ae86d6a916f\&evmVersion=null) to get started with a template code for a ZRC-20 contract. You can explore the code in the MyToken.sol file and make any changes you'd like to make.

Compile the code and move to the deployment tab.

![](<../.gitbook/assets/Screenshot 2022-03-30 at 12.57.48 PM.png>)

If the environment isn't Injected Web3, change that. You should either see Custom (79) network or Custom (91) network depending on whether you're using mainnet or testnet.&#x20;

![](<../.gitbook/assets/Screenshot 2022-03-30 at 1.47.35 PM.png>)

Finally, it's time to deploy. Choose MyToken contract in the contract dropdown and input the constructor argument. In this case, the argument will be the amount of the token you're creating. When you've done both these things, click deploy. You will get a metamask popup confirmation for the deploying transaction. Within no time (thanks to Zenith's fast block time), your contract will be deployed. You can interact with it within Remix in the Deployed Contracts section.&#x20;
