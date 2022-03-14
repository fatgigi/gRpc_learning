# gRpc_learning

### Successful command line
protoc --proto_path=proto --go_out=pb --go_opt=paths=source_relative proto/processor_messasge.proto

protoc --proto_path=proto --go_out=pb proto/*.proto

go test ./...