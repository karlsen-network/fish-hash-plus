## KarlsenHashV2
This is the implementation of fishhash+ algorithm adapted to the karlsen network new algorithm karlsenhashv2
This version is supposed to be as closed as possible to the original fishhash plus version.
Notable modifications are :
* the header size of 80 bytes (no impact here)
* the blake3 hash result are always of 32 bytes
* the hasher use a hash512 seed as input like in the first version of fishhash

## FishHash
This is a work in progress version of Iron Fish's new mining algorithm FishHash. It was created by community member Lollidieb. It is a modified version of the [Ethash mining algorithm](https://ethereum.org/en/developers/docs/consensus-mechanisms/pow/mining-algorithms/ethash/) that uses the [blake3 hashing algorithm](https://github.com/BLAKE3-team/BLAKE3) as well as some other customizations.

### Specification
Lollidieb has created a [specification](./FishHash.pdf) for the algorithm.

### Discussion
Discussion has been happening in the IronFish Discord [mining channel](https://discord.com/channels/771503434028941353/828803908067262484). There is also a [post](https://discourse.ironfish.network/t/proposal-memory-hard-mining-algorithm-fishhash/88) for the proposal on the IronFish Discourse website.
