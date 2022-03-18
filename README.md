# apigatewaylambda

This project creates:
- A REST API Gateway;
    - Endpoints enabled:
        - GET /customers;
        - POST /customers;
        - GET /customers/{id};
        - PUT /customers/{id};
        - DELETE /customers/{id};
- A Lambda function as the backend of the API
    - CloudWatch Logs enabled;

## Helpful links

- [What is Amazon API Gateway?][1]
- [Working with REST APIs][2]

[1]: https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html
[2]: https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-rest-api.html