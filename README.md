# Automatic-scaling-and-load-balancing-with-EC2-and-ALB
Automatic scaling and load balancing with EC2 and ALB

**Lab scenario**

In this lab, you will be a Cloud Practitioner at a company that is considering moving applications to the cloud. Your boss is interested in learning about the value proposition of the cloud, especially in relation to elasticity and agility.

**Objectives**

1] Execute the tasks to deploy a web application on EC2 instances behind an elastic load balancer with automatic scaling

2] Demonstrate the benefits and processes of elasticity and high availability in the AWS Cloud

3] Understand the core AWS services required to run a web application in the AWS Cloud

**Your project assignment**

**Your Manager**

Hi SHARUKHAN! Thanks for working on this project for our team.
The executive team at our company is concerned about our ability to scale applications during peak periods of demand. I’d like you to demonstrate the features of Amazon Web Services (AWS) that can be used to easily enable elasticity for applications.

Your task is to demonstrate how an Amazon EC2 Auto Scaling group with an Application Load Balancer (ALB) can automatically scale based on the number of connections made through the ALB. The EC2 instances should display a web page that is generated based on content stored in an Amazon S3 bucket.

Where to complete your work

The project will be assigned one ticket at a time in a series of tasks. To complete these tasks, you’ll need to use the workspace provided. You can launch by clicking below or at any time by clicking the button in the top right of the screen.

**Task 1**

**Create S3 bucket and upload artifacts** 

You will now create an Amazon S3 bucket in which to store the file that will be used to generate the HTML web page. The bucket will need to be configured for public access. Once the bucket has been created upload the file and ensure it is publicly accessible.

**Task 2**

**Create Target Group and Application Load Balancer**

You will now create a Target Group and Application Load Balancer. The ALB will be configured to distribute connections to the Target Group which will contain the instances launched by the Auto Scaling group.

**Task 3**

**Create Launch Template and Auto scaling group**

You will now create a launch template with user data that picks up the index.txt file from the Amazon S3 bucket and configures a web page on EC2 instances that describes which Availability Zone the EC2 instance is located in. You will also create an Amazon EC2 Auto Scaling group that uses the launch configuration.

**Task 4**

**Test with multiple connections from browser**

You will now test causing a scale-out event by using your web browser to create multiple connections to the Application Load Balancer.
