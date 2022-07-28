## Init subgraph
```
graph init \
  --product subgraph-studio \
  --from-contract 0x5fbdb2315678afecb367f032d93f642f64180aa3 \
  --network http://localhost:8545 \
  --abi goldabi.json \
  Gold
```

## Build subgraph
```
npm run build
```

## Create subgraph to local network
```
npm run create-local
```

## Deploy subgraph to local network
```
npm run deploy-local
```