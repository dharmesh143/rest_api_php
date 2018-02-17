# rest_api_php
This is REST API example developed in PHP

Step 1 : you need to create MySQL Database to make it working
Step 2 : Import SQL file in your database under SQL/rest_api.sql
 Two tables are created just to create demo application.
 
Step 3 :  Update database connection setting in config\database.php
		
	// specify your own database credentials
    private $host = "localhost";
    private $db_name = "rest_api";
    private $username = "root";
    private $password = "";
    public $conn;
	
	
Step 4 : Now you are ready to access data using REST API.

API will return formate in Json.

Below API content 

1.0 Read Products
1.1 Product Object
1.2 Create "read.php" file
1.3 Add Product "read()" method
1.4 Output : http://localhost/api/product/read.php

2.0 Create Product
2.1 Create create.php file
2.2 Product create() method

3.0 Read One Product
3.1 Create read_one.php file
3.2 Product readOne() method
3.3 Output http://localhost/api/product/read_one.php?id=60

4.0 Update product
4.1 Create “update.php” file
4.2 Product update() method

5.0 Delete Product
5.1 Create “delete.php” file
5.2 Product delete() method

5.0 Search Products
5.1 Create "search.php" file
5.2 Create "search()" method
5.3 Output : http://localhost/api/product/search.php?s=shirt

6.0 Paginate Products
6.1 Create "read_paging.php" file
6.2 Create "core.php" file
6.3 Create "readPaging()" method
6.4 Create "count()" method
6.5 Get "paging" array
6.6 Output

11.0 Read Categories
11.1 Category object
11.2 Create "read.php" file
11.3 Category "read()" method
11.4 Output : http://localhost/api/category/read.php



 
 
 
