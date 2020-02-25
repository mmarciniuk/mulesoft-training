# DB setup

MySQL database
db:
  host: "mudb.learn.mulesoft.com"
  port: "3306"
  user: "mule"
  password: "mule"
  database: "training"

American table: american
Account table: accounts
Account list URL:  http://mu.learn.mulesoft.com/accounts/show 
or if using mulesoft-training-services.jar application:
http://localhost:9090/accounts/show.html

* MySQL database as URL and driver name
URL: jdbc:mysql://mudb.learn.mulesoft.com:3306/training?user=mule&password=mule
Driver class name: com.mysql.jdbc.Driver

* Derby database
URL: jdbc:derby://localhost:1527/memory:training
Driver class name: org.apache.derby.jdbc.ClientDriver