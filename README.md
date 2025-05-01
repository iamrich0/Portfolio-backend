# Portfolio-backend!
This diagram explains the structure of the whole fullstack project:
![Frontend+Backend](https://github.com/user-attachments/assets/9964355b-2bff-4c85-84f2-f72c9ab4a7bc)


# Project structure
The backend consists of AWS API Gateway that sits between the user and backend services. The API Gateway accesses Lambda function, which updates a DynamoDB visitor counter table. Each HTTP request increments the visitor counter and an updated value is then returned to the user through Lambda and API Gateway.
