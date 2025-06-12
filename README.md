# Restaurant-Management
 Offline restaurant Management System using C# and mvc pattern. The project has been developed by 3 groupmates including myself as a third year course project. The course name for this project was Object Oriented Programming-2 (Using C# and its relevant technologies).

***Features***

• Manager

o	Can login to the system using own user id and password

o	Has full access over data table

o	Can observe the entire sells report from the data table

o	Can manage and view manager info, employee info, food information

o	Search option for any data from data table




• Employee


o	Can login to the system using own user id and password

o	Can insert and update food order but cannot delete a previous data

o	Cannot have view to the whole data table but his own orders only

o	Can view own information and update them whenever necessary

o	Search option for food info

o	Can view food information


--------------------------------------------------------------x----------------------------------------------------------------

***Data Dictionary***

1. Admin Entity: 

   Key: Primary

	Name 	         Data_Type  	   Length 	   Nullable

	user_id	          INTEGER	         10	        No

	name	          VARCHAR	         50	        No

	designation	  VARCHAR	         50	        No

	email	          VARCHAR	         50	        No

	Salary	          INTEGER	         20	        No


3. Employee Entity:

   Key: Primary

	Name	           Data Type 	     Length	   Nullable

	user_id	            INTEGER	         10	       No

	name	            VARCHAR	         50	       No

	designation	    VARCHAR	         50	       No

	email	            VARCHAR	         50	       No

	Salary	            INTEGER	         20	       No


5. Food Entity:

   Key: Primary

 	Name              Data Type 	     Length	    Nullable

	food_id	           INTEGER	         10	         No

	food_name	   VARCHAR	         50	         No

	food_type	   VARCHAR	         50	         No

	price	           INTEGER	         50	         No


7. Food Order:

   Key: Primary

 	Name                Data Type 	        Length	     Nullable

	order_id	     INTEGER	            10	           No

	food_id              VARCHAR	            10	           No

	food_name	     VARCHAR	            50	           Yes

	food_quantity	     INTEGER	            10	           No

	unit_price	     INTEGER	            10	           No

	total_price	     INTEGER           	    20	           No

	vat	             INTEGER	            10	           Yes

	discount	     INTEGER	            10	           Yes

	grand_total	     INTEGER	            30	            No




***Requirements Filled Up***
	
•	At least 2 types of User

•	One Complete Repository

•	Database Connection Class

•	Normalized DB (2NF)	

•	Search Option for all users 

•	Separate Login Table

•	Object Oriented Programming Principles

•	Application Layer (Form Design)

• 	Database CRUD operations

•	All the forms are connected

•	n-Tier architecture followed

•	Entity Classes


