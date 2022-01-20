# test-serverless-golang-lambda
Deploy 2 golang aws lambda functions using serverless framework

## Require
1. go
2. serverless framework
3. Setup your AWS profile for serverless

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
