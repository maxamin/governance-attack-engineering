# Glossary

- **Governor:** on-chain voting contract pattern (OpenZeppelin, Compound).
- **Proposal threshold:** voting power required to create a proposal.
- **Quorum:** minimum votes for a proposal to be valid.
- **Voting delay:** time between proposal and voting start (snapshot point).
- **Snapshot block:** the block (or timestamp) at which voting power is measured.
- **Checkpoint:** stored historical voting-power value used by `getPastVotes`.
- **Delegation:** assigning one's voting power to an address (possibly oneself); required by `ERC20Votes`.
- **Timelock:** delay between approval and execution.
- **Canceller role:** timelock role allowed to cancel queued operations; often held by a guardian.
- **Guardian / security council:** small accountable body with scoped emergency powers such as veto or pause.
- **Time to defend:** total of voting delay, voting period and timelock: the window defenders have to react.
- **Snapshot (tool):** off-chain signed voting platform.
- **Snapshot strategy:** the rule that computes voting power for a Snapshot space.
- **oSnap:** UMA's optimistic execution of Snapshot results through a Safe module.
- **Safe transaction hash:** EIP-712 hash of a Safe transaction that signers approve.
- **Optimistic governance:** actions pass unless vetoed.
- **Metamorphic contract:** contract replaced with different code at the same address.
- **State diff:** the set of storage, balance and code changes produced by simulating a transaction.
