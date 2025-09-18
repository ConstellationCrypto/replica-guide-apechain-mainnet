# Running a Replica node

This repo is setup to easily run apechain replica nodes. Simply run `docker-compose up` to bring a replica node up locally.

The nodeConfig file is prepopulated with apechain parameters. The current setup uses a public rpc url for the Arbitrum One rpc and stores node data in docker volume.

Replace the arbitrum one rpc url with your own to avoid being rate limited.

## Image
`public.ecr.aws/i6b2w2n6/nitro-node:apechain-2.0.0`

## Snapshot
September 16 2025:
https://caldera-chain-data-snapshots.s3.us-west-2.amazonaws.com/exported-snapshots/nitro-apechain/nitro-apechain-2025-Sep-16.tar

