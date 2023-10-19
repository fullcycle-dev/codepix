# CodePix

### Imersão Full Stack && Full Cycle

#### Comandos utilizados

```sh
go mod init github.com/fullcycle-dev/codepix
```

```sh
protoc --go_out=application/grpc/pb --go_opt=paths=source_relative --go-grpc_out=application/grpc/pb --go-grpc_opt=paths=source_relative --proto_path=application/grpc/protofiles application/grpc/protofiles/*.proto
```

```sh
cobra-cli init
```