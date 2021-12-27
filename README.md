# Vite NFT Standard Proposal by Mike (@wepsree)

Included in this repo are my proposals for the Solidity++ equivalents of [ERC721 and ERC721Enumerable](https://eips.ethereum.org/EIPS/eip-721). Also included is an [ERC721Metadata](https://docs.openzeppelin.com/contracts/2.x/api/token/erc721#ERC721Metadata) Solidity++ equivalent and possible solution for mirroring Solidity++ 0.4 NFT's to SOlidity++ 0.8.

The code and documentation go hand in hand. The code in this repo was heavily influenced by [openzeppelin-contracts](https://github.com/OpenZeppelin/openzeppelin-contracts), but has been modified to compile in Solidity++ `^0.4.3`.

The structure of this repo is:
1. Any file directly under `contracts` is an example
2. Any file directly under `contracts/standards` is a base contract/interface that should be inherited from
3. Any file directly under `contracts/standards/utils` is just for helper functions

**THIS CODE HAS NOT BEEN FULLY TESTED**, but the functions I've tested seem to work.