# Portfolio-backend![Frontend+Backend](https://github.com/user-attachments/assets/223268e9-5953-4ab6-90bf-4f1ac159201e)

# Project structure
The backend consists of AWS API Gateway that sits between the client and backend services. The API Gateway accesses Lambda function, which updates a DynamoDB visitor counter table. Each HTTP request increments the visitor counter and an updated value is then returned to the client through Lambda and API Gateway.
