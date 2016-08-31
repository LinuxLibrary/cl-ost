# CONNECT TO AN EC2 INSTANCE THROUGH SSH :
------------------------------------------

If you have an EC2 instance running Linux and you want to connect to that then follow the below steps.

To connect to an EC2 instance you should have the public key (.pem file) of that host.
While creating EC2 instance at Step 7 (Review and Launch) it will ask to create a public key.
If you a key already then you can use that by selecting the key you have.

- Have your Public key ready in your home directory.
- Change the permissions of that key file to 0400
- Know the default user depending on the Linux flavor you are using
	- Amazon Linux	- ec2user
	- RHEL		- root / ec2user
	- SUSE Linux	- root / ec2user
	- Fedora Linux	- fedora / ec2user
	- Ubuntu	- ubuntu
- Know the public DNS or IP of that instance
- Connect to your instance through ssh in the below way
	# ssh -i <my_key>.pem <user>@<DNS/IP>
