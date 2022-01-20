# test-serverless-golang-lambda
Deploy 2 golang aws lambda functions using serverless framework

## Requirement
1. go
2. serverless framework
3. Setup your AWS profile for serverless

## Initialize
### No need to rerun this command, I did it before
```
go mod init hello
```
### Run these commands to install dependencies before building
```
go get github.com/aws/aws-lambda-go/lambda
go get github.com/aws/aws-lambda-go/events
```

## Build & Deploy
```
make build
make deploy
```
