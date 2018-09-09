# Building an API by AWS API Gateway and Lambda

AWS API Gateway allows you to connect mobile and web applications with business logic hosted on AWS Lambda. With API Gateway, you could create and operate APIs for backend services. In this example, I'll build a API for the querying of the sum of two integers.

## Create a Lambda Function
1. Choose runtime. To start a simple example, choose 'Aurhor from scratch', then give a name to the function and choose python 3.6 as rutime.
2. Choose role. The role defines the permissions of the function.
3. Add triggers. Add API Gateway as Trigger and when the function part is done, turn to the gateway.
