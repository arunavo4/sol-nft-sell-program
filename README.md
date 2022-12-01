# Repo for Holding only the contract [Fixed]

Fixed issues with the Contract.

[sol-sell-escrow](https://github.com/arunavo4/sol-sell-escrow)

## Development Cycle
```
# Make sure you’re on the localnet.
solana config set --url localhost
# And check your Anchor.toml file.

# Code…

# Run the tests.
anchor test

# Build, deploy and start a local ledger.
anchor localnet
# Or
solana-test-validator
anchor build
anchor deploy

# Switch to the devnet cluster to deploy there.
solana config set --url devnet
# And update your Anchor.toml file.

# Airdrop yourself some money if necessary.
solana airdrop 5

# Build and deploy to devnet.
anchor build
anchor deploy

```
