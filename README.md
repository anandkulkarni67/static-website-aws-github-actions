# A Static website deployed to AWS cloudfront served from S3 with CICD implementation using AWS CodePipeline

## download and install dependencies
```
npm install
```

## Compiles and hot-reloads the project for development
```
npm run serve
```

## Compiles and minifiesthe project for production deployment
```
npm run build
```

## AWS Stacks creation
```
Recommended Order:
1. Application
2. Security
```

## GitHub integration
```
1. Go to the source code github repository.
2. Click on Settings.
3. Click on Environments on the side panel and create a 'production' environment.
4. Create three secret environment variables.
   AWS_REGION ( AWS region in which resources are deployed )
   AWS_ACCOUNT_ID ( ID of the AWS account where resources are deployed )
   OIDC_ROLE_NAME ( you can find this value in the output of Security cloudformation stack )
```
