# Reading-Notes

                        **Class-07-reading**
#### What code does the server actually run?
* 
#### What Express/HTTP operations map to CRUD operations?
* We can define GET, POST, PUT and DELETE urls as well as what code is executed when a request to that endpoint is received.
#### What does res.send() do?
* It is a method that sends data in a proper format to the client.
#### What is the order of operations for the three categories of middleware (handler, application, route)?
* application middlewar :- Run whenever the server receives a request
* route middleware :- Runs whenever the server receives a request to a specific url endpoint
* handler middleware :- Runs when the server receives a specific method request
#### What is the parameter next used for?
* To call the next middleware in the chain.
