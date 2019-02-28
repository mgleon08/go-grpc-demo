# gRPC

```go
// 產生 .pb 檔案
protoc --go_out=plugins=grpc:. *.proto

// 先啟動 server
go run ./server/main.go

// 再啟動 client
go run ./client/main.go
```