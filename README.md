# testgosdk

generate proto and grpc code
need to install
go install google.golang.org/protobuf/cmd/protoc-gen-go@v1.28@latest
go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@latest

protoc --go_out=. --go-grpc_out=. ./src/test.proto