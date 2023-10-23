<img src="WebContent/Assets/Based Records Logo.png" width=600px></img>

Based Records is our group project for COSC 304 (Introduction to Databases, Fall 2022) at UBCO. It is set up to run on docker using a container running SQL Server and a container running Apache Tomcat. Tomcat processes the Java servlets, and SQL Server stores the information for the products, orders, customers, and more. The focus of the project was to build a website that communicates with a database using SQL, through a database driver.

## Contributors

This was a group project wherein the original working repository can be [found here](https://github.com/shh1v/BasedRecords).

The contributors of the project were:

1. [Louis Lascelles-Palys](https://github.com/LouisLP)
2. [Justin Schoenit](https://github.com/justino599)
3. [Dhruv Bihani](https://github.com/DhruvBihani)
4. [Shiv Patel](https://github.com/shh1v)

## Running the website locally

To run the site locally, use docker to run `docker-compose up` in the root directory. After the containers have finished starting up, go to [http://localhost/shop/loaddata.jsp](http://localhost/shop/loaddata.jsp), then you should be able to access the home page via [http://localhost/shop](http://localhost/shop).

## Screenshots

### Home Page

![image](https://user-images.githubusercontent.com/77038122/207140660-6231edf1-cac9-44ea-9051-3b53e26dae46.png)

### Shopping Cart

![image](https://user-images.githubusercontent.com/77038122/207140978-8e790f61-4af5-4dd1-94a5-a35a2a44d5a0.png)

### Product Page

![image](https://user-images.githubusercontent.com/77038122/207145040-b25000b5-ab30-4838-8c5f-833f16655843.png)
