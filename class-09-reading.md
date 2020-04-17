# Reading-Notes

                        **Class-09-reading  API Server**
#### Describe a use-case where param middleware would come in handy.
*Param middleware can be useful for validating the request param before moving on to the route.

#### What are the two ways to add middleware in-between Mongoose and MongoDB interactions?
*The two ways to add middleware between Mongoose and MongoBD interactions are by using the pre or the post hooks.

#### What is the difference between a join by reference and a virtual join?
*MongoDB is not a relational database, but you can perform a left outer join by using the $lookup stage. The $lookup stage lets you specify which collection you want to join with the current collection, and which fields that should match

#### What do localField and foreignField mean?
*localField: the field we want to join by in the local collection (the collection we are running the query on) foreignField: the field we want to join by in the foreign collection (the collection we want to join with) as: the name of the output array for the results.

[Home](https://eyob1984.github.io/reading-notes)
