
####打开镜像 

docker exec -it 镜像ID bash

docker logs -f cli


####复制本地东西到 docker镜像中
docker cp   本地地址文件    Docker的Name  :    docker里面的地址
docker cp chaincode_example02.go cli:/opt/gopath/src/github.com/hyperledger/fabric/examples/chaincode/go/chaincode_example02

####简单打印docker日志
