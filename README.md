## Initialize
```
go mod init hello
go get github.com/aws/aws-lambda-go/lambda
go get github.com/aws/aws-lambda-go/events
```

## Deploy
```
make build
make deploy
```