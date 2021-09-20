# MongoDb Relationships

## What are the three types of relationships?
one to one, one to many, and many to many.

## What are the benefits of the traditional linking of relationships instead of Embedding
It improves the performance of the application and lowers the overall IO load. 
In the article example it states that it will make it so when you add extra comments it will not cause the the document size to go over its maximum 16 mb.

## What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?
There are different ways to link or embed your relationships. It will depend on what the relationships are, and what you are wanting to do with them. Many to many relationships require multiple queries.