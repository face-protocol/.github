# Hey ✌️!

Figma with designs - https://www.figma.com/file/fRMbvf8LOjJl04ouEJb3ZE/Untitled?type=design&node-id=0%3A1&mode=design&t=TUOBaZWcERKzb40q-1

App code - https://github.com/face-protocol/app

Smart contracts code - https://github.com/face-protocol/smart-contracts

## Thesis ##
Reputation means nothing in DeFi. However, reputation backed by money means a lot.

## Solution ##
Reputation protocol, where members of communities give each other ETH as proof of trust and that they know each other in real life

## How it works ##
1. Users can create their own communities and set parameters such as the deposit fee, required number of members for accepting new members, community name, and logo.
2. To request membership, applicants must submit a non-refundable fee. If not accepted, the fee will not be returned.
3. Applicants need to find community members who are willing to accept them (this is okay in small communities).
4. Once approved, new members receive "reputation boosts" worth a fraction of the joining fee.
5. Members can use these boosts to enhance the reputation of other members.
6. The accumulated reputation can be utilized in DeFi protocols that are built on top of our protocol.

## Examples of Use: ##
- Since reputation is directly tied to money, it enables them to participate in DeFi protocols.
- If these communities are adopted, they will be displayed on your profile in web3 social networks, similar to how your current company is shown on Twitter and LinkedIn.
- Verify status without revealing personal information. Anonymous founders can verify their education and past statuses at an address without disclosing personal details. (Note: The community determines the data required for verification when submitting an application. Some communities may require verification of platforms like LinkedIn, which may involve de-anonymization. However, users can decide whether to join such communities.) For instance, founder Blur could verify being an alumnus of Standard and YCombinator.

## Here are some examples of protocols that could be built on top of our protocol: ##
- Lending (e.g., AAVE, Gearbox): Use reputation as collateral.
- Non-collateral lending with community guarantors: Use your friends' reputation as collateral.
- Portfolio management protocols with a security fund: Utilize reputation as a security fund to cover portfolio losses.
- Guarantee service for P2P trades: Hold reputation until the trade is completed.
- DAO voting without tokens: Vote using reputation.
- Derivatives based on reputation: Place bets on reputation growth or loss.

## Sybil-resistant design ##
- **Cannot be controlled by wealthy members.** Reputation is non-tradable; It can only be received from other members
- **Cannot join with a fake identity.** Approvals require a personal acquaintance, but it is common in tight-knit communities
- **Cannot be dominated by a small group.** Reputation can be revoked for bad behavior
- **Protection against the use of multiple identities.**  On-chain recording of the last update date and the number of updates ensures that a user cannot easily swap identities
