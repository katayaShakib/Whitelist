# Whitelist Contract

Give your early supporters access to a whitelist for your upcoming NFT collection.

The first 10 users who join the whitelist will be able to mint a NFT for free, while everyone else will have to pay to mint one!

I Have deleted the front-end since this is a simple enough contract.

You can simply tinker with the contract by adding users to the whitelist through Etherscan, as the contract has been verified on it.

Go to Sepolia Etherscan and search up this contract address "0x383ed2396239dCe1C9c25068Df93a5B91Ea93356", and go to the Contract tab there.

Go to the Read Contract tab and click on numAddressesWhitelisted, then go to the Write Contract tab and first click on Connect to Web3 - this will prompt you to connect your wallet to Etherscan. Once you have connected a wallet, click on addAddressToWhitelist and then click on Write.

This should pop open your wallet to confirm a transaction. Confirm the transaction, and then wait for it to go through. You can click on View your transaction on Etherscan to check it's status.

Once the transaction is successful, go back to the Read Contract tab, refresh, and click on numAddressesWhitelisted. It should be incremented.