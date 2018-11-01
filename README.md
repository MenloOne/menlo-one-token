# Menlo ONE Token

The smart contracts for the [Menlo One][menlo] ONE Token and crowdsale.

![Menlo](Menlo.png)


## Contracts

Please see the [contracts/](contracts) directory.


## Artifacts

Please see the [build/](build) directory.


## The ONE Token

The ONE Token's contract address is:

```
0x4d807509aece24c0fa5a102b6a3b059ec6e14392
```

Click here to see the [ONE Token on Etherscan][etherscan].

The code was audited by [Hosho and contained no critical errors](https://medium.com/menlo-one/hosho-audits-menlo-one-smart-contract-with-zero-vulnerabilities-644e6e6b9ebb).


## Background

The ONE Token pretty closely follows the [ERC-20](https://en.wikipedia.org/wiki/ERC-20) standard, except for added features to make it compatible with Menlo One products. 

The ONE Token was deployed on Sep-16-2018 10:29 AM UTC. The Menlo ONE Token crowd sale started Sep-17-2018 at 9:00 AM UCT which lasted for 30 days.

Contracts are written in [Solidity][solidity] and were tested using [Truffle][truffle] and [ganache][ganache].

We use [Open Zeppelin][zeppelin] code for `SafeMath`, `Ownable`, `ERC20Basic`, `PausableToken`, `BurnableToken` and `StandardToken` logic which is included in the contracts.


[menlo]: https://menlo.one
[ethereum]: https://www.ethereum.org/

[solidity]: https://solidity.readthedocs.io/en/develop/
[truffle]: http://truffleframework.com/
[ganache]: https://github.com/trufflesuite/ganache-cli
[etherscan]: https://etherscan.io/token/0x4d807509aece24c0fa5a102b6a3b059ec6e14392
[zeppelin]: https://github.com/OpenZeppelin/openzeppelin-solidity
