npm i -g serverless
serverless create --template aws-nodejs --path api-serverless-aws-java

mvn clean install
serverless invoke local --function hello
    serverless invoke --function hello