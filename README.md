# ZeroGold (Whitepaper)

**ZeroGold (0GOLD) is the "official" token of the Zer0net and [Zeronet Explorer](https://github.com/d14na/zeronet-explorer).**

> The Zer0net delivers greater information freedom, identity protection and data privacy than the Internet, without the creepy funk of the Darkweb. You're welcome!

## TL;DR

1. Never, ever, ever tell anyone how much **`0GOLD`** you're hodling.
2. Identical to Bitcoin, **`0GOLD`** is capped at 21 million bricks.
3. Unlike Bitcoin, **`0GOLD`** hodlers are rewarded with premium subscriptions and rewards.

## Token Address *(source code verified)*

### [0x6ef5bca539A4A01157af842B4823F54F9f7E9968](https://etherscan.io/token/0x6ef5bca539A4A01157af842B4823F54F9f7E9968)

## ERC20-Compatible Token

    Name         : ZeroGold
    Symbol       : 0GOLD
    Total Supply : 21M (21,000,000)
    # Decimals   : 8 (0.00000001)

## 0Brick

    = 1.00 0GOLD

## 0Grain

    = 0.000001 0GOLD

## 0Dust

    = 0.00000001 0GOLD
    = 0.01 0Grain

*i.e. the smallest possible unit will be `1 0Dust`*

## List of Commerce Possiblities

1. Zitetag 1-year registration ***(~$9.99)***
2. ZeroDelta exchange fee ***(0.30%)***
3. Ad | Sponsorship fee ***(30%)***
4. ZeroVPN [ Hodlre\* ***(free)*** | Elite Subscriber ***(based on usage)*** ]

** A Hodlre Subscription grants premium access to anyone HODLing at least `1 0GOLD` token (subject to change).*

## ZeroTree

> A repository of ZeroGold collected from premium services rendered within the community.

##### Solidity Example *(this is NOT actual code)*

    // Pick gold from the tree.
    function pick (uint _dust) public {
        ZeroGold.transfer(msg.sender, _dust);
    }

    // Shake the balance from the tree.
    function shake () public {
        uint goldBalance = ZeroGold.balanceOf(msg.sender);
        ZeroGold.transfer(msg.sender, goldBalance);
    }

## Questions?

support@d14na.org
