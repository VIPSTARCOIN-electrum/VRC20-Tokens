# Background

This Project is refers to [ethereum-lists/tokens](https://github.com/ethereum-lists/tokens) repository.

# Tokens

Information related to tokens. VRC-20(VIPS-Token) compliant or compatible only, please.

## Fields:

### Mandatory

-  `symbol`:    Short ticker style symbol of token.
-  `name`:      Longer human version of token.
-  `address`:   VIPSTARCOIN (or other chain) address of VRC-20 token(Token  contract address).
-  `decimals`:  The decimals of the token. As Number and not String.


### Optional

-  `logo`:      An optional logo of your token. Must be a **square** (recommended: 128x128) PNG w/ transparent background. Please compress using https://tinypng.com/
-  `support`:   A support email, support URL, or other way people can get assistance regarding the token.
-  `github`:    Where token or project-related code lives.
-  `community`: Twitter, Reddit, Slack or wherever else people hang out.
-  `website`:   Official URL of the website.


# The assembled lists

This repository has the tokens as single files. This makes it easier for contributors to add new tokens, for reviewers to get a good view on the change and also makes it easier to merge in tokens from other sources. Projects will most likely want to use the assembled lists. The CI server is already building them - so you can just [go to the commit-list](https://github.com/VIPSRARCOIN-electrum/VRC20-Tokens/commits/master) and click on the green checkmark behind the last commit. There you see kontinuum/run - and the details link there brings to the assembled files on IPFS.

# Usages

- [TREZOR](https://trezor.io) - they even [import via IPFS ;-)](https://github.com/trezor/trezor-common/blob/078cf07658a99888adca19e3284864a5354da550/ethereum_tokens-gen.py#L7)
- please let us know when you do (you don't need to but it would be nice!)

# A last note

This list is maintained by volunteers in the community &amp; people like you around the internet. It may not always be up to date, and it may occasionally get it wrong. If you find an error or omission, please open an issue or make a PR with any corrections.
