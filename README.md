# Home

Welcome to Boost documentation.

### What's Boost?

Boost is a protocol for programmable distribution of ERC-20. The protocol allows you to deposit ERC-20 tokens and select a strategy which define who can claim the ERC-20 and how many tokens they can claim. The strategy is enforced by an oracle called the "guard".  The guard issue signed message with EIP-712 to allow anyone that pass the requirements defined by the strategy to claim ERC-20.

### Strategies

Boost strategies define who can claim the ERC-20 and how much each address can claim. The strategies are run offchain by guards. The first strategy that we released is used to reward voters on a Snapshot proposal.&#x20;
