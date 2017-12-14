# COMP586Client
Application URL:
http://recipe-book-comp586.s3-website-us-west-2.amazonaws.com/ Hosted on AWS S3

Server side Code:
https://github.com/koshasheth24/COMP586Server

Backend hosted on EBShttp://default-environment.n2u6uc6b6f.us-west-2.elasticbeanstalk.com
Spring MVC based implementation of backend.
Dependency injection and JPA for DB access.
Authentication and authorization handled via tokens through Firebase Authentication.

MySQL DB hosted on AWS EC2 moviereview.cwbu8r5mq6wc.us-west-1.rds.amazonaws.com

Main Page contains some recipes.
Authorized user can add/remove recipes
Unauthorized user can only view recipes
User can also add Ingredients to ingredient list based on reciepe.
