# CREATING AN EBS (ELASTIC BLOCK STORE) VOLUME:
-----------------------------------------------

Let us see how to create an EBS volume and attaching to an instance.

- Go to the EC2 dashboard
- On the left pane click on Volumes
- Click on Create Volume
- Mention the required size
- Select the availability zone (If required)
- Click on Create
- You should notice the status of your new vol as "Available"
- Now right click on the volume
- Click on attach volume
- Select the instance which you want to have this volume on
- Click on Attach
- Login to that instance and check whether it exists or not
- Now you can use this volume as like a standard volume in Linux.

NOTE:
Be sure to remove that volume and the snapshot if this volume is not in use.

Before deleting this volume please make sure you have backup of IMP data.

- Unmount the volume on the host / instance
- Go to Volumes in the EC2 Dashboard
- Select the volume and click on the Actions and then on Dettach
- Wait till the status is Available
- Now again click on Actions and then on Delete Volume
- Confirm to Delete
