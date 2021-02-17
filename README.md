# ThemiyaSandakelum-REST-API-using-JAVA-and-Spring-Boot-with-Mysql-main
I create a mobile application to allow coffee shop customers to order coffee online. I Create simple DB Structure to store the product details.I Create simple REST API to view products and place a new order. I Use Spring Boot as the framework to develop the REST API. I Use MySQL as the Database.


1.	Insert MySQL Database to xamp or wamp.It is attached the this file (database name=coffee_shop) 

2. 	Now we can run the Application class and test. With Eclipse, you can see the Spring Boot logo appears in the Console view. 

3. 	We’ve started Tomcat server on localhost with its default port 8080. Let’s check it out in our browser: http://localhost:8080 You can change the port using application.properties is set server.port=8181 

4. 	We can show the list of coffee items, http://localhost:8080/products/ 

5. 	We can search the products by using id http://localhost:8080/products/{id}

6.	We can order the product by using postman select by POST http://localhost:8080/orders/add we have to enter body tab form data or else
	  We can update the order by using postman select by PUT http://localhost:8080/orders/update/{id}
	  We can update the order by using postman select by PUT http://localhost:8080/orders/delete/{id}
