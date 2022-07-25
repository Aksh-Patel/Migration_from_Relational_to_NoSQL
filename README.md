# Migration_from_Relational_to_NoSQL
<b> Core Idea:</b>
<li> In this project, we have designed our own algorithm for migration which we have implemented as a web application which takes postgres schema, mongodb connection string and access paths as input and create mongodb collections as output. 
<li> It performs schema extraction, then runs our algorithm and from the results, it performs embedding and linking between collections and finally populate mongodb collections.
<li> We had created a small frotend using PyWebio which takes necessary input and shows success or Failed message.<br>
  
## How it Works?
Example Database [Entertainment Booking System]<br>
We have 5 tables in ER Diagram.<br>
## Schema Diagram
![image](https://user-images.githubusercontent.com/58646076/180844328-276d62cb-4892-4ba2-ad73-f27023bf9d3c.png)

## HomePage of the Application:
![image](https://user-images.githubusercontent.com/58646076/180844473-22f60a3c-25f7-4b28-aaba-1ea12c8c6e19.png)

Note: Access path is a text file, which is given to the input to prioritized some collections which are frequently queried out. The migration Algorithm takes care about these access paths.<br>
## Example of Acesss path for our Entertainment Booking System:<br>
![image](https://user-images.githubusercontent.com/58646076/180845210-58a97b3b-2bb3-47f2-8cea-0b0d6dfe8b2c.png)

## Processing of the Algorithm
![image](https://user-images.githubusercontent.com/58646076/180845088-cfd08890-987c-4f1d-b85f-140732292ce2.png)

## Migration Done Sucessfully
![image](https://user-images.githubusercontent.com/58646076/180844885-d83e7c6c-7016-4945-8e00-ef6fda587c89.png)

### This project was done as the Summer Research Internship.
