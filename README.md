# Examples:

# Get a transaction by hash from the full node HTTP API:


curl http://x:api-key@127.0.0.1:14037/tx/\
  4674eb87021d9e07ff68cfaaaddfb010d799246b8f89941c58b8673386ce294f


# Get a raw transaction by hash from the full node RPC API:


curl http://x:api-key@127.0.0.1:14037 \
  -X POST \
  --data '{ \
    "method": "getrawtransaction", \
    "params": [ "4674eb87021d9e07ff68cfaaaddfb010d799246b8f89941c58b8673386ce294f"] \
  }'


# Get a transaction by hash from the "primary" wallet HTTP API:


curl http://x:api-key@127.0.0.1:14039/wallet/primary/tx/\
  4674eb87021d9e07ff68cfaaaddfb010d799246b8f89941c58b8673386ce294f


# Get a transaction by hash from the wallet RPC API:


curl http://x:api-key@127.0.0.1:14039 \
  -X POST \
  --data '{ \
    "method": "gettransaction", \
    "params": [ "4674eb87021d9e07ff68cfaaaddfb010d799246b8f89941c58b8673386ce294f" ] \
  }'
