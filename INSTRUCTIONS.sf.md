## Use `cast` and useful command we did

```shell
# To be put in .envrc
export ETH_RPC_URL=<rpc_url>
export STAKING_GRAPH_CONTRACT=0x00669a4cf01450b64e8a2a20e9b1fcb71e61ef03
export SF_INDEXER_ADDRESS=0x35917c0eb91d2e21bef40940d028940484230c06
```

### Calls

Find indexer capacity:

```shell
cast call "$STAKING_GRAPH_CONTRACT" 'getIndexerCapacity(address)' "$SF_INDEXER_ADDRESS"
```
