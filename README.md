# Awesome Aragon List

A list of awesome Aragon stuff!

## Aragon 101

High level intro to Aragon goes here.

- [Wiki](https://wiki.aragon.org)
- [Permissions](https://aragon.helpscoutdocs.com/article/21-permissions) - Explains how permissions work on Aragon.

## Using Aragon

- [Aragon User Guide](https://wiki.aragon.org/tutorials/Aragon_User_Guide/)

## Hacking On Aragon

Tools and guides to build awesome Aragon stuff.

Aragon CLI

- [AragonCLI DAO Commands](https://hack.aragon.org/docs/cli-dao-commands)

[Docs](https://hack.aragon.org/docs/getting-started)
- [aragonPM](https://hack.aragon.org/docs/apm-intro.html)
- [aragonOS](https://hack.aragon.org/docs/aragonos-intro.html)
- [aragonAPI](https://hack.aragon.org/docs/api-intro.html)
- [aragonUI](https://hack.aragon.org/docs/aragonui-intro.html)
- [aragonCLI](https://hack.aragon.org/docs/cli-intro)
- [Radspec](https://github.com/aragon/radspec)

## Tutorials

- [App Development Guide](https://hack.aragon.org/docs/tutorial)
- [App Publishing Guide](https://hack.aragon.org/docs/guides-publish)
- [Deploying Custom Organizations](https://hack.aragon.org/docs/guides-custom-deploy)

## Aragon Apps

Apps you can plug into your Aragon DAO.

### Tokens & Financial Stuff

- [Token Manager](https://aragon.helpscoutdocs.com/article/18-token-manager) - An app that creates and manages tokens that can be used in Aragon DAOs.
- [Vault](https://github.com/aragon/aragon-apps/tree/master/apps/vault) - A vault that can be configured to be managed by DAO token holders (requires using [Finance](https://aragon.helpscoutdocs.com/article/20-finance) app as a front-end).
- [Finance](https://aragon.helpscoutdocs.com/article/20-finance) - A front-end for the [Vault](https://github.com/aragon/aragon-apps/tree/master/apps/vault) app.
- [Agent](https://aragon.org/agent) - A "smart vault" that allows the DAO to act like an externally owned account (EAO). You can send tokens directly to the Agent's contract address and Agent can do anything you can do via Metamask, however, actions are routed through a DAO vote by default (but you can change this just like with any app).
- [Redemptions](https://github.com/1Hive/redemptions-app) - Redeem tokens against a basket of white-listed tokens held in the DAO.
- [Projects](https://github.com/AutarkLabs/planning-suite/tree/dev/apps/projects) - An app that allows the DAO to award bounties for working on GitHub Issues.
- [Allocations](https://github.com/AutarkLabs/planning-suite/tree/dev/apps/allocations) - Allows the DAO to set a budget of tokens to allocate on a weekly basis.
- [Rewards](https://github.com/AutarkLabs/planning-suite/tree/dev/apps/rewards) - Dividends for DAO members.
- [Payroll](https://github.com/aragon/aragon-apps/tree/master/future-apps/payroll) - Recurring payments from the DAO.

### Governance

- [Voting](https://aragon.helpscoutdocs.com/article/19-voting) - The default voting app that ships with most Aragon DAOs.
- [Furarchy](https://github.com/levelkdev/futarchy-app) - Futarchy markets for governance.
- [Dot Voting](https://github.com/AutarkLabs/planning-suite/tree/dev/apps/dot-voting) - Dot voting for DAOs (only works for signalling or distribution of allocations)
- [Delay](https://github.com/1Hive/delay-app/blob/master/docs/user-guide.md) - The Delay app is a [forwarder](https://hack.aragon.org/docs/forwarding-intro). It can delay, pause, and resume an action initiated by a DAO member.

### Other Stuff

- [MyID](https://github.com/MyBitFoundation/MyBit-DAO.tech/tree/master/apps/MyID) - No idea. Please submit a PR if you figure it out.
- [MyTokens](https://github.com/MyBitFoundation/MyBit-DAO.tech/tree/master/apps/MyTokens) - No idea. Please submit a PR if you figure it out.
- [Livepeer Transcoder Manager](https://github.com/videoDAC/livepeer-aragon) - This app empowers a "Decentralized Autonomous Organisation" (DAO) on Aragon's platform to govern the roles of Delegator and Transcoder in Livepeer's protocol.
- [DappNode NFT Manager](https://github.com/eduadiez/DAppNodeNFT) - No idea. Please submit a PR if you figure it out.

## Aragon DAO Templates

- [Dandelion Orgs](https://1hive.org/getting-started-with-dandelion-organizations/) - MolochDAO V2 on Aragon minus rage-kick.
- [Aragon Fundraising](https://fundraising.aragon.black/) - A clasic [DAICO](https://ethresear.ch/t/explanation-of-daicos/465) model on Aragon.
- [Aragon Classic](https://mainnet.aragon.org/#/create) - The Company, Reputation, and Membership orgs are the same template (token manager, vault, and voting apps) with slightly differnent restrictions on token transfers.

## Unorganized

- [Empower The DAO apps](https://github.com/empowerthedao) - Aragon apps for Uniswap, Livepeer, and more stuff.
- [DAOnuts](https://github.com/daonuts) - Apps for dual-token voting, subscriptions, token claims, and more.
- [1Hive](https://github.com/1hive/) - Apiary DAO explorer, app installer, gardens, dandelion, and more.
