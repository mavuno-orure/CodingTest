# CodingTest

1.	Write a method to find the 2nd largest element in a binary search tree. Below is the printed output. 
![Node](https://user-images.githubusercontent.com/61843513/198829701-6e09b13a-c741-4a0c-b0aa-aa6b5ad7c93a.PNG)

2.	Given an array of integers, find the highest product you can get from three of the integers. Below is the printed output.
![GFG](https://user-images.githubusercontent.com/61843513/198829772-23646ee4-c028-4a70-baac-8fb06793059a.PNG)

3.	What is a singleton? Write a class demonstrating a singleton and its implementation.

In object-oriented programming, a singleton class is a class that can have only one object (an instance of the class) at a time. After the first time, if we try to instantiate the Singleton class, the new variable also points to the first instance created. So whatever modifications we do to any variable inside the class through any instance, affects the variable of the single instance created and is visible if we access that variable through any variable of that class type defined. 
Remember the key points while defining class as a singleton class that is while designing a singleton class: 
 .	Make a constructor private.
 .	Write a static method that has the return type object of this singleton class. 
Use of Singleton in Java
Singletons can be used while working with databases. They can be used to create a connection pool to access the database while reusing the same connection for all the clients. For example,

We have created a singleton class Database.
The dbObject is a class type field. This will refer to the object of the class Database.
The private constructor Database() prevents object creation outside of the class.
The static class type method getInstance() returns the instance of the class to the outside world.
In the Main class, we have class type variable db1. We are calling getInstance() using db1 to get the only object of the Database.
The method getConnection() can only be accessed using the object of the Database.
Since the Database can have only one object, all the clients can access the database through a single connection.


4.	Implement a queue with 2 stacks. Your queue should have an enqueue and a dequeue method and it should be "first in first out" (FIFO). Use (java or python). Below is the output with java program.
![Queue](https://user-images.githubusercontent.com/61843513/198829786-db6f28a7-93bc-4151-8201-8b0750926595.PNG)

5.)	We want the order ID of every order in January and February, 2019 including the customer Name on each Order. Write a  query to do that:
![SQL Query](https://user-images.githubusercontent.com/61843513/198829795-017d9a5d-0ec1-49f1-9c00-9dc649fcb3c7.PNG)
