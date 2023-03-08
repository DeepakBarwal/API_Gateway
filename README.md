FRONTEND - MIDDLE-END - BACKEND

- We need an intermediate layer between the client side and the microservices
- Using this middle end, when client sends request, we'll be able to make decision that which microservice should actually respond to this request
- We can do message validation, response transformation, rate limiting
- We try to preapre an API Gateway that acts as this middle-end
