[![Go Report Card](https://goreportcard.com/badge/github.com/AndreaM16/aws-sdk-go-bindings)](https://goreportcard.com/report/github.com/AndreaM16/aws-sdk-go-bindings)

# aws-sdk-go-bindings
Helper to easily access some [aws-sdk-go](https://github.com/aws/aws-sdk-go)'s methods. It also contains multiple methods to cover tricky problems like preparing and sns default message and unmarshal an image coming out from a stream. At the moment it covers SNS, DynamoDB, Rekognition and S3.

## Development

If you want to fork it or just use it in local, edit `internal/configuration/configuration.json` by setting your aws options like:

```
{
  "region" : "eu-central-1",
  "target_arn" : "arn:aws:sns:eu-central-1:your_aws_accound_id:some_arn_name"
}
```
