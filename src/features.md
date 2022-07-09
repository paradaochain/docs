# ParaDAO Features

### Contribution based Voting Power

One of the benefits of having a DAO is to distribute decision making.
In many cases, each member of the DAO has voting power depending on the
amount of governance tokens they have.

This makes sense in many cases as they have more "skin in the game".

In some cases, however,
DAO may want to have voting power reflecting the contribution done by the individual.
This contribution allows the "promotion" of individuals into different roles which maps to different
voting power.

As we move towards [decentralised identity] solutions with [verifiable credentials] that can be tied to
onchain accounts,
and projects that provide [identity aggregation services],
it becomes easier to prevent sybil attack on DAO voting that is based on contribution. I.e. someone
cannot just use many accounts to gain the same amount of voting power as someone who has contributed).

TODO: links in code

[identity aggregation services]: https://litentry.com/
[verifiable credentials]: https://www.w3.org/TR/vc-data-model/
[decentralised identity]: https://www.w3.org/TR/did-core/

### Prediction Market for DAOs

By providing variety of voting power does not automatically increase engagement,
ensure a great voting turnout,
or cover all decisions that needs to be made by DAOs.

ParaDAO leverages prediction markets to encourage participation in different forms.

#### Voting

For example,
Early voters for a [binary prediction market] will have little certainty of the outcome and therefore if the vote automatically provide a position in a prediction market,
early voters will be rewarded more than the late voters, when the outcome is more predictable.

#### Content promotion

For example, in the case of a `Fanclub`, there can be prediction market created by the DAO to

[binary prediction market]:

### Support by staking

In addition to direct donation , ParaDAO has a native currency that is minted according to a [bonding curve] where the rewards can be distributed to the staker or the DAO treasury.

[bonding curve]:

### Community types

ParaDAO initially has composable options that are designed to support 2 types of DAOs

#### 1. Individual support

Inspired by Patreon / Substack,
individuals who produces valuable contents may be supported by a community / fan base through a DAO.

In this case,
the DAO roles will only be the admin (content producer) and the supporters,
where the supporters can participate in some polls / suggestion and the admin will have full control over the DAO treasury.

#### 2. Interest Groups

Inspired by meetup.com,
a group of individuals may want to contribute to say a software code base, a meetup events etc.
Some members of the DAO should be rewarded for their contributions,
and some other members may just be users of a software or participants of an event.

In this case,
the DAO will have a selection of roles of which the users in each role may be able to vote / execute subset of actions only.
It is also likely in this case that the treasury is managed by proposals and votes.
