# APIs

## [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

1. **What does REST stand for?** Representational State Transfer
2. **REST APIs are designed around a ____.** Resource - any kind of object, data or service accessible by a client.
3. **What is an identifier of a resource?** Give an example. A unique ID for a customer. AN example would be a customer order or account. 
The URI would identify that account.

```js
https://adventure-works.com/orders/1 
```

4. **What are the most common HTTP verbs?** GET, POST, PUT, PATCH, DELETE
5. **What should the URIs be based on?**The resource and the operations of that resource.
6. **Give an example of a good URI.**

```js
https://adventure-works.com/orders // Good

https://adventure-works.com/create-order // Avoid
```

7. **What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?** A "chatty" API is when a large number of small resources are exposed in a request. Too many web requests put a larger load on the server. Such APIs should be avoided to lessen the load on the server.

8. **What status code does a successful GET request return?** 200 (OK)
9. **What status code does an unsuccessful GET request return?**  404 (Not Found) or 204 (No Content)
10. **What status code does a successful POST request return?** 201 (Created)
11. **What status code does a successful DELETE request return?** 204 (No Content) or 400 (Bad Request)
