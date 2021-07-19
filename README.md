# Spring-Security-Student_API-JWT

In this guide, we've taken a look at how to create and manage the authentication and authorization of the students.

We have created a Spring Boot Applicaton with the help of Rest API and JWT where you can register new user and you will recieve a JWT token. And by that token you can access the data of the users as per there certain roles.

Skills: Spring Boot Rest API, JPA, MYSQL, Lombok, PostMan, JWT

After running the Spring Application,

1- Insert the roles inside the role table

![1st step](https://user-images.githubusercontent.com/84781683/126105319-b8b4a7aa-e5e6-4e4d-8dc0-7cd5cf908c81.PNG)

2- Enter the SignUp and enter records

![2nd step](https://user-images.githubusercontent.com/84781683/126105700-3184ad9b-ff58-4ebd-9c5a-0fb37d8ecf17.PNG)

3- Enter more records as much you want
   (The password here is in Bcrypt Format)

![3rs step](https://user-images.githubusercontent.com/84781683/126105792-4746468b-fe99-4895-b4d3-8de09279beaf.PNG)

4-Enter the username and password in SignIn, Copy the access token

![4th step](https://user-images.githubusercontent.com/84781683/126105915-a448aee2-c471-4ea7-ab32-e7413fa56059.PNG)

5-Open the admin API and in get request open the header and insert Authorization in KEY and Bearer + (access token) in Value

![5th step](https://user-images.githubusercontent.com/84781683/126106081-209f69fe-b20f-4359-b728-7280b13ca6ce.PNG)

6-If you try to access different role API you will receive Unauthorized error

![6th step](https://user-images.githubusercontent.com/84781683/126106176-00f2f66a-6920-4e88-8e57-c67df6074716.PNG)

7-For that you need to sign in again as your user role mentioned during signup and copy the access token

![7th step](https://user-images.githubusercontent.com/84781683/126106323-b81fbf3a-05c0-4320-b632-6e685c9670da.PNG)

8- Follow step 5 but this time in user API

![8th step](https://user-images.githubusercontent.com/84781683/126106374-80e42211-dea6-47fd-8dbf-d1f90bfac388.PNG)



