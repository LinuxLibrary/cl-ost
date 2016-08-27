# ACCESS YOUR S3 BUCKET FROM YOUR MACHINE THROUGH CMD LINE

For this exercise you need to download the latest version of s3cmd tool.

- Go to http://s3tools.org/download
- Download the tar ball of the latest version
- Unzip the contents of that tar to /var/local/src
- Switch to root
- Get into the s3cmd directory
- Run "python setup.py install"
- Go to your "Security Credentials page" of your AWS account
- Get your Access Key and Secret key
- Now Configure your s3cmd to use those credentials
	- s3cmd --configure
	- Paste your Access Key
	- Paste your Secret Key
	- Leave all the defaults
- Test s3cmd "Try to list your S3 buckets with 's3cmd ls'"
