```
export GOPATH=`pwd`

go get github.com/go-redis/redis
go get github.com/hashicorp/memberlist
go get stathat.com/c/consistent

git submodule update --init
cd rocksdb && make static_lib
```
