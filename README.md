# Migration_from_Relational_to_NoSQL
Core Idea:
In this project, we have made an application which takes name and access path as input and can get mongoDB collections as an atlas in mongoDB compass. The algorithm can extract all the needed schema information such as fetch tables, primary key, referred table,reference table etc for given schema. After schema extraction, algorithm will embed or the bases of set of rules. After migration completed, collections are populated in mongoDB compass.

How it Works?
Example Database [BasketBall Training Manangement System]
image

We have 17 table in SQL Schema.
Schema Diagram
![image](https://user-images.githubusercontent.com/58646076/180844328-276d62cb-4892-4ba2-ad73-f27023bf9d3c.png)

HomePage of the Application:
![image](https://user-images.githubusercontent.com/58646076/180844473-22f60a3c-25f7-4b28-aaba-1ea12c8c6e19.png)

Note: Access path is a text file, which is given to the input to prioritized some collections which are frequently queried out. The migration Algorithm takes care about these access paths.
Example of Acesss path for our Entertainment Booking System:
![image](https://user-images.githubusercontent.com/58646076/180844684-d7273795-0860-4b5d-b3d6-ea23583db115.png)

Processing of the Algorithm
![image](https://user-images.githubusercontent.com/58646076/180844817-f21e5f7c-ff70-4e15-8902-4cfc6f6be6fc.png)

Migration Done Sucessfully
![image](https://user-images.githubusercontent.com/58646076/180844885-d83e7c6c-7016-4945-8e00-ef6fda587c89.png)

This project was done as the Summer Research Internship.
