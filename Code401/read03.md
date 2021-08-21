# **Express**

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/1024px-Unofficial_JavaScript_logo_2.svg.png" width="200">

## Name 3 real world use cases where you’d want to change the request with custom middleware

- getting data from the database
- getting data from an API server
- Authanticating a user

## True or false: The route handler is middleware?

False

## In what ways can a middleware function end the process and send data to the browser?

By using the next method you can control the request and send data to the server.

## At what point in the request lifecycle can you “inject” middleware?

right after the request is sent, the middleware function is called.

## What can cause express to error with “Request headers sent twice, cannot start a second response”

trying to modify response headers after the request body has been sent to the browser

### Middleware : [Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle.](https://expressjs.com/en/guide/using-middleware.html)

### Request Object : [The request object allows you to submit a POST or GET request to an URL. Essentially it provides a way to make REST API requests to another URL](https://www.branchcms.com/learn/docs/developer/twig/request-object#:~:text=The%20request%20object%20allows%20you,save%20it%20within%20the%20CMS.)

### Response Object : [he object which communicates between the server and the output which is sent to the client](https://www.4guysfromrolla.com/webtech/faq/Beginner/faq3.shtml#:~:text=One%20of%20the%20most%20important,Server%20Pages%20script%20where%20needed.)

### Application Middleware : Middleware that is applied between and application and the operating system

### Routing Middleware : Middleware that is used to perform certain actions when moving from one route to another in a website application

### Test Driven Development : [a software development process relying on software requirements being converted to test cases before software is fully developed](https://en.wikipedia.org/wiki/Test-driven_development)

### Behavioral Testing : [The testing of external behavior of the program](http://www.codekul.com/blog/what-is-behavioral-testing/)
