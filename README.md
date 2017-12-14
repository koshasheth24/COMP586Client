# COMP586Client
Application URL:
http://recipe-book-comp586.s3-website-us-west-2.amazonaws.com/ Hosted on AWS S3

Features:
Login
By default, it fetches data from Array
On login, right top corner has manage button,
Click on fetch data to fetch all teh recipes from Database.
Add new recipe
View Recipe details
Edit recipe
Add ingredients to shopping list
Ingredients tab shows the ingredients.

Register

Logout
Cannot edit/add recipes

Server side Code:
https://github.com/koshasheth24/COMP586Server

Backend hosted on EBShttp://default-environment.n2u6uc6b6f.us-west-2.elasticbeanstalk.com
Spring MVC based implementation of backend.
Dependency injection and JPA for DB access.
Authentication and authorization handled via tokens through Firebase Authentication Identity as a service.


MySQL DB hosted on AWS EC2 moviereview.cwbu8r5mq6wc.us-west-1.rds.amazonaws.com

Main Page contains some recipes.
Authorized user can add/remove recipes
Unauthorized user can only view recipes
User can also add Ingredients to ingredient list based on reciepe.
