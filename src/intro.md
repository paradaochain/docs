# Introducing ParaDAO

ParaDAO provides tools for communities with the same passion / shared interests to come together to organise amongst themselves to acheive a common goal.
The decentralised application that allows communities to create a DAO easily with out of the box governance models for managing:

- DAO treasury (moving of funds to certain purposes: host an event (offchain), staking / swapping (onchain))
- DAO details (Updating some onchain /decentalised storage data of the DAO)
- Proxy execution ( Enable the DAO to take part in other DApps, for example joining / voting in
  another DAO )
- Oracle for prediction market creation and referee

ParaDAO is not only a tool, it in itself is a DAO and members are the DAOs created.
This ensures that ParaDAO continues to provide useful features to support the community.

Discover our features relating to:

- [Contribution based Voting Power](./voting_power.md)
- [Engagement by Prediction Markets](./prediction_market.md)
- [Dao Types](./dao_type.md)
- [(Coming Soon) support by staking](./support_with_staking.md)

## Components (Current)

- A parachain node with the `pallet-contract` to host the set of smart contracts for for DAO creation
- A relay chain node to simulate staking of relay chain native tokens
- Frontend allow users to create DAOs easily, allow DAO members to do proposals, votes, etc
- integration with Zeigeist sdk

### Why Ink!

We have use Ink! because it was important for this set of tools to be easily deployable on different
parachains.

ParaDao is a tool to allow people to collaborate in the most convient way,
and would like to be available for any chain that supports the substrate's smart contracts.

## Inspiration

This project is heavily inspired by many project that have been very well thoughtout.
We adapted our own twists as a PoC for the hackathon but we would like to credit:

- daodao.zone
- daohaus.club
- xdao.app
