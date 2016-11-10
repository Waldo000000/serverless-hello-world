# serverless-hello-world

Simple demo of the [Serverless framework](https://serverless.com/), that simplifies creating and using AWS Lambda functions.

## Deploy
To deploy to a dev stage in default AWS region (us-east-1):
```serverless deploy```

The output will indicate the endpoint created by the framework, e.g.:
```
endpoints:
  GET - https://<some string>.execute-api.us-east-1.amazonaws.com/dev/hello
```

Browse to that address to see the response from the deployed function.
