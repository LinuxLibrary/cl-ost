# CREATING A CUSTOM AMI :
-------------------------

We can create a custom AMI from a running machine. If we have a machine running
with all the configs we need then we can create our own AMI from that machine.

- Go to the EC2 dashboard
- Ensure the Status Checks of the instance are looking good.
- Right click on the instance and select "Image" and then select "CreateImage"
- Provide "Image name", "Image Description" and click on "Create Image"
  This will take some time.

- To create an EC2 Instance from this image go to "My AMIs" in the left pane a
  -nd select your custom AMI.

To remove this AMI go to AMIs in the EC2 dashboard, right click on the AMI and
select Deregister.
