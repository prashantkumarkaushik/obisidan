### Requirements
* Proper Login and register API
* Post API includes pagination and sorting
* Proper input validation handling  -> to the database
* Proper exception handling
* Role based authentication
* JWT based authentication
* Document all rest API's so that consumer can easy understand
*  Deploy the backend application on any cloud platform -> AWS


### Technologies
* Spring boot
	* Java 8+
	* Maven (build tool)
	* IDE
	* Apache tomcat
	* Spring core, Spring security(JWT), Spring data (JPA) hibernate,
* MySql Database
* Postman Rest Client
* Swagger for proper API documentation
* AWS (EC2) for the deplyment

### Resources
* User
	* id
	* name
	* email (username)
	* password
	* about
* Category
	* category_id
	* title
* Post
	* post_id
	* title
	* content
	* image
	* ==user_id==
	* ==category_id==
* Comment
	* comment_id
	* comment content
	* ==post_id==
	* ==user_id==

* Role
	* role_id
	* role_name
#### Layered Architecture
* Postman Client -> Controller (API layer) -> Services (business logic) -> Repositories (DAO Data access object) -> Database
