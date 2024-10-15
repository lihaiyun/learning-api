# Learning API

[Learning App](http://nyp-learning-app-dev.s3-website-ap-southeast-1.amazonaws.com){:target="_blank"}

## Environment Variables:
- APP_PORT = 8080
- APP_SECRET = 013720de-bd04-40b2-9a8c-ca625c831265
- CLIENT_URL = http://nyp-learning-app-dev.s3-website-ap-southeast-1.amazonaws.com
- DB_HOST = <database-id>.<random-id>.ap-southeast-1.rds.amazonaws.com
- DB_NAME = learning_dev
- DB_PORT = 3306
- DB_PWD = your_password
- DB_USER = admin
- NODE_ENV = production
- TOKEN_EXPIRES_IN = 30d

## commands in EC2:
sudo yum install mariadb105  
mysql -h hostname -u username -p  
CREATE SCHEMA learning_dev;  
SHOW DATABASES;  

## eb commands:
eb list  
eb use  
eb swap  
eb printenv  
eb setenv key=value  
eb deploy  
