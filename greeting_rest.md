##### Building a RESTful Web Service
You have to write a "hello world" RESTful web service using MEAN stack.

###### What you’ll build:
You’ll build a service that will accept HTTP GET requests at:

```
http://localhost:8080/greeting
```
and respond with a JSON representation of a greeting:

```
{
    "id":1,
    "content":"Hello, World!"
}
```
You can customize the greeting with an optional name parameter in the query string:

```
http://localhost:8080/greeting?name=User
```
The name parameter value overrides the default value of "World" and is reflected in the response:

```
{
    "id":1,
    "content":"Hello, User!"
}
```