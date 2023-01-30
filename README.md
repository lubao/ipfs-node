# ipfs-note
Note for IPFS implementation.

## What is a IPFS Repo
Repo represents all persistent data of a given ipfs node. https://github.com/ipfs/kubo/blob/master/repo/repo.go#L21

## Kubo Add 
https://github.com/ipfs/kubo/blob/master/docs/add-code-flow.md

## IPFS GO DS S3
https://github.com/ipfs/go-ds-s3

## Kubo Map of Implemented Subsystems
https://github.com/ipfs/kubo#map-of-implemented-subsystems

## IPFS article
https://github.com/ipfs/awesome-ipfs#articles

### Textile.io
You can find a lot of stuff on DHTs(how do we find content & peers in the network?)
https://medium.com/textileio

### Understanding the IPFS White Paper part 1
https://decentralized.blog/understanding-the-ipfs-white-paper-part-1.html

### Understanding the IPFS White Paper part 2
Understanding the IPFS White Paper part 1

# Dive deep

## https://www.freecodecamp.org/news/technical-guide-to-ipfs-decentralized-storage-of-web3/

## https://www.freecodecamp.org/news/from-zero-to-interplanetary-hero-7e62f7d4427/

## Package importer implements utilities used to create IPFS DAGs from files
https://github.com/ipfs/go-unixfs/blob/master/importer/importer.go

## https://github.com/ipfs/camp/tree/master/DEEP_DIVES

# libp2p swithch (swarm)

## https://blog.cryptostars.is/libp2p-the-network-engine-behind-ethereum-polkadot-and-ipfs-bc2686affa6d

###Transport

###Security
The peer id is a cryptographic hash of a peer’s public key.

###Peer routing
Peer routing in libp2p uses a distributed hash table to iteratively route requests closer to the desired peer id using Kahdemlia algorithm.

###Content discovery
That can be achieved by content routing interface with same implementation of Kahdemlia algorithm.

###Pub Sub

## https://docs.libp2p.io/concepts/appendix/glossary/#swarm
