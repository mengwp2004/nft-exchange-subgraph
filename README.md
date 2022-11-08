# Example Subgraph


## 1. Install the Graph CLI
npm install -g @graphprotocol/graph-cli

## 2. Initialize your Subgraph
graph init --product hosted-service --from-example

## 3. write you ubgraph
```
Manifest (subgraph.yaml) - The manifest defines what datasources your subgraph will index
修改subgraph.yaml文件
修改合约地址为： 0x2b165c265a0d20e697dfce2b9c4af27b5a458611
修改network为： mumbai
```

## 4. Deploy your Subgraph
```
yarn codegen
graph auth --product hosted-service xxxxx
graph deploy --product hosted-service mengwp2004/nftstudy
```

## 5 query log
```
查询的endpoints：
https://cloud.hasura.io/public/graphiql
```

## 6 参考
https://thegraph.com/docs/en/cookbook/quick-start/
