# Creating an EC2 Virtual Server:
---------------------------------

- Login to your AWS Management Console
- Go to the EC2 Dashboard
- Click on Launch Instance

Let us go for a Basic EC2 instance for now and leave the defaults as is.

Step 1:
	Now you 'll see a wide variety of AMI(Amazon Machine Image)s.
	A typical AMI is just like a template. We'll have some pre-defined
	and some custom AMIs as well. Even we can prepare our own AMI. Wel
	-l we'll see that later.

	For now please select an AMI. 
NOTE : IF YOU ARE USING A FREE TIER ACCOUNT OR ELSE YOU NEED SOME FREE AMIs
       THEN IN THE LEFT PANE CLICK ON (Free Tier Only) CHECK BOX AND SELECT
       AN AMI.

Step 2:
	Select the type of instance

Step 3:
	Configure the instance details
	Here you can do the following things
	- Change the number of instances
	- Network settings
	- Defining and/or assigning IAM Roles	
	- Change the shutdown behavior
	- Enable CloudWatch for monitoring ( * PAID * )
	- Also can do some advance tasks like running some predefined scrip
	  -ts by placing the scripts in the User Data block.

Step 4:
	Add Storage

Step 5:
	Tag instance
	- This one will be useful when you have multiple instances running.

Step 6:
	Security Group
	- This will allow you to configure some securities to that instance
	- Name the security group and the change the inbound and/or outboun
	  -d rules according to your plans / views.

Step 7:
	Review and Launch
	- At this step you can go through all your configurations also can
	  change if needed.
	- While launching it will prompt for the public key if you already
	  have a key then you can mention it over there or else you should
	  create a new key.

- Once your instance is running fine with all the checks good then you can
  connect to your instance with the public DNS provided.
