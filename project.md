## Understanding the LEMP stack implementation.
### Setting up an EC2 instance.
A new EC2 instance is created in order to implement the LEMP stack.
![create_EC2](./img/1%20create%20new%20instance.png)
This created instance is then connected to and this is done in git bash termial.
![connect_to_instance](./img/2%20connect%20to%20ec2%20instance.png)

### Step one (Installing Nginx web server) 
The instance is updated so as to get all up and running.
![updating_server](./img/3%20updating%20server.png)
Nginx server is installed in the EC2 instance.
![install_nginx](./img/4%20install%20nginx.png)
Nginx server up and running.
![server_up](./img/5%20nginx%20server%20up.png)
Accessing server locally through git bash terminal.
![accessing_server_locally](./img/6%20server%20locally%20accessible.png)
Connecting to server via the web browers.
![via_the_web](./img/7%20connected%20to%20nginx%20server.png)

### Step two (Installing mysql)
Mysql is installed in the EC2 instance.
![Mysql_installed](./img/8%20mysql%20server%20installed.png)
Connecting to mysql.
![mysql_connected](./img/9%20connected%20to%20mysql.png)

### Step three (installing php)
php is installed and to understand files from mysql and fpm.
![php_installed](./img/10%20installing%20both%20php%20-fpm%20and%20-mysql.png)
A web root directory is created.
![web_root_dir](./img/11%20create%20a%20root%20web%20dir.png)
The directory is personalized for that web server.
![dir_personalization](./img/12%20dir%20personalization.png)

### Step four (configuring Nginx to use php processor)
The configuration needed for Nginx to use php processor is activated using the nano editor.
![configuration_nginx_php](./img/13%20activating%20config.png)
The configuration is successful.
![config_successful](./img/14%20nginx%20config%20success.png)

### Step five (testing php with nginx)
A html file is forwarded by nginx.
![html_file](./img/15%20html%20file%20fowarded%20by%20nginx.png)
The server is accessed via the web to test its response.
![nginx_responding](./img/16%20nginx%20responding.png)
Php response is also tested to see if the server recognises php.
![web_showing_phpinfo](./img/17%20web%20page%20showing%20info.png)

### Step six (retriving data from mysql database with php)
A database is created in the mysql interface.
![creating_database](./img/18%20create%20database.png)
The database is secured by setting a password.
![database_password](./img/19%20setting%20password%20to%20database.png)
Then the database is given the pamission to access all files.
![database_pamission](./img/20%20giving%20pamission%20to%20database.png)
The created database is accessed so as to either create items or retrive info if any.
![accessing_database](./img/21%20accessing%20created%20database.png)
This is the current information about the database.
![database_info](./img/22%20database%20info.png)
From the information about the database, its seen that the database is empty, so a table is created so as to add some items to the database.
![creating_table](./img/23%20creating%20table%20in%20mysql.png)
A row is added to the table created in the database.
![add_row](./img/24%20inserting%20a%20row%20into%20DB.png)
Multiple rows are added to the table.
![more_rows](./img/25%20rows%20inserted%20in%20the%20DB.png)
Viewing the items added to the table in the database via the web browser.
![web_page_showing_mysql_content](./img/26%20web%20page%20showing%20mysql%20content.png)



