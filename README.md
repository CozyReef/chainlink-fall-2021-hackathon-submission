# Chainlink Fall 2021 Hackathon Submission

Note: Private repos have been shared with `Chainlink-DevRel`. If you'd like us to spin up a game instance of `Slingshot Sailors` please reach out to us at [@TheCozyReef](https://twitter.com/thecozyreef)

A megaproject containing all of our repos for the Fall 2021 Chainlink
Hackathon.

We've submoduled all the relevant repo's that we've worked on over the course
of the hackathon, pinned to the commit hash for when we provided our
submission.

Below is a brief summary of each repo in question.

## cozyreef

A monorepo for the core Cozy Reef dapp. It is a React NextJS based dapp
leveraging hardhat for automation. Our core contracts, tests, deploys, and
front end experience are all stored in this project.

## art-generator

A small tool used to generate NFT artwork. It currently leverages a
configuration file to specify how NFT's are supposed to be combined, which
leaves it extensible for much more fine tuned generation leading into our NFT
launch.

## infrastructure

Our Terraform infrastructure. We Terraform nearly everything we need to host
and deploy our application, and this infrastructure as code is stored in our
infra repo.

## prototype-chainlink-proof-of-reserves

Our prototype for proof of reserves using Chainlink Oracle nodes and External
Adapters. This prototype shows an end to end flow of verifying NFT ownership on
the Rinkeby testnet by submitting a verification request on Mumbai. We plan to
pull this into our core CozyReef project and leverage it to help mint tickets
for users who want to join our ecosystem.

## prototype-nftmint

Our first prototype at the very beginning of the project. This is archived but
it helped introduce us to NFT's and contracts and show us how to work with all
the different technologies to build and deploy NFT's.

## prototype-chainlink

Our second prototype where we looked into Chainlink VRF's and Keepers. Again,
this prototype served as an introduction into the technologies we would end up
using in the CozyReef project, including Typescript and typechain to really
empower us to develop quickly.
