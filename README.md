Technologies - Spring Boot, Maven, H2, Postman
--------------------------------------------
1) Below endpoint will create sample data in H2.

http://localhost:8080/mockupData

![alt text](https://github.com/Raghuj95/CustomerRewardPoints/blob/main/Showcase/mockupdata.png)

2) Get the customer total earning points and monthly wise total earning points

http://localhost:8080/getRewardPoints?name=customer1

![alt text](https://github.com/Raghuj95/CustomerRewardPoints/blob/main/Showcase/customer1.png)

3)Get the customer total earning points and monthly wise total earning points

http://localhost:8080/getRewardPoints?name=customer2

![alt text](https://github.com/Raghuj95/CustomerRewardPoints/blob/main/Showcase/customer2.png)

4)Incase of user is not found

http://localhost:8080/getRewardPoints?name=customer10

![alt text](https://github.com/Raghuj95/CustomerRewardPoints/blob/main/Showcase/nocustomer.png)


To Run Junits 
-----------
Unit Testing  Junit (run com.points.PointsServiceTest.java class)

![alt text](https://github.com/Raghuj95/CustomerRewardPoints/blob/main/Showcase/Junits.png)

For Dockerization
-----------------
use dockerfile to create image
