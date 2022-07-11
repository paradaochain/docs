# Future Work

## Improvments

### DAO Roles

Currently there are only 3 types of roles,
ideally roles should be created when creating the DAO.
Each role should map to specific permission(s) applicable.
These permissions should also be flexible and members can vote to change them.

### Proposal

Proposal should have different expiration, threshold

### Voting

Staked tokens should contribute to the voter's weight,
there should be a snapshot for the weight of the votes at time of proposal

### Zeitgeist

We had spent significant about of time to try to connect ZG parachain to the relay chain in order to
directly create Prediction Market with XCM.

This was the steps we had researched, but were only able to get to Step 2.5 (Able to finalize 1 block)

1. add zg docker to docker-compose
2. register on relay chain
3. zg produce blocks
4. zg \<\> paradao channel
5. add xcm-pallet to paraao chain to call zg to create PM, [example](https://github.com/LaurentTrk/sublink-pallets/tree/main/xcm)
6. add the xcm-pallet to the paradao chain runtime + test
7. add extension (a function and add it to the contract-pallet config in the runtime) to paradao chain to extend contract to call the xcm-pallet in step 5,
   [example](https://github.com/LaurentTrk/sublink-pallets/blob/72ea5678c3fa0d493680cf101843d3d1d9897ceb/ink/contract/src/lib.rs)
