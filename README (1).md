<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Build a Virtual Private Cloud

**Project Link:** [View Project](http://nextwork.ai/projects/aws-networks-vpc)

**Author:** Narte, Wensly Anthony  
**Email:** wenslynarte@gmail.com

---

## Build a Virtual Private Cloud (VPC)

![Image](http://nextwork.ai/sympathetic_brown_vibrant_date/uploads/aws-networks-vpc_2facf927)

---

## Introducing Today's Project!

In this project, I will learn about VPC even though I have no prior knowledge or background in it. My goal is to understand the basics by following the step-by-step procedures and demonstrating the process throughout the project.

### What is Amazon VPC?

 Amazon VPC (Virtual Private Cloud) is a private virtual network in AWS where I can launch and manage cloud resources securely. It is useful because it lets me control the network settings, such as IP addresses, subnets, and internet access, while keeping my resources organized and protected.

I used Amazon VPC to create a private virtual network for my AWS resources. I created a custom VPC, added a subnet, enabled auto-assign public IPv4 addresses, attached an Internet Gateway, and configured the route table so the subnet could connect to the internet. This helped me understand how Amazon VPC is used to organize and securely manage cloud resources while controlling network access.

### Personal reflection

This project took me 1 and half hours

One thing I didn't expect in this project was how easy it was to understand. At first, I thought it would be difficult because I had no background knowledge about Amazon VPC. However, the clear step-by-step explanations made it much easier to follow and I was able to understand each part of the project.

---

## Virtual Private Clouds (VPCs)

### What I did in this step

In this step, I will create a VPC because it serves as a private virtual network where I can securely launch and manage cloud resources. It provides a controlled networking environment for the project.

### How VPCs work

In my own understanding, a VPC is a private network in the cloud that helps protect my resources from public access. Only authorized users or services can access them unless I make them public.

### Why there is a default VPC in AWS accounts

There was already a default VPC in my account ever since my AWS account was created. This is becausAWS has a default VPC so users can quickly launch cloud resources without having to set up a network first. It provides a ready-to-use network with basic configurations, making it easier to start using AWS.e...

![Image](http://nextwork.ai/sympathetic_brown_vibrant_date/uploads/aws-networks-vpc_2facf927)

### Defining IPv4 CIDR blocks

To set up my VPC, I had to define an IPv4 CIDR block, whiIn my own understanding, an IPv4 CIDR block is a way of defining a group of IP addresses for a network. It helps AWS know the size of the network and how many resources, such as servers, can have their own IP addresses within that network.ch is...

---

## Subnets

### What I did in this step

In this step, I will create a subnet to Launch a subnet inside the VPC.


### Creating and configuring subnets

a subnet is a smaller network inside a VPC. It divides the VPC into smaller parts so resources can be organized and managed more efficiently.

### Public vs private subnets

my subnet is not considered a public subnet yet because it does not have a route to the Internet Gateway. This means the resources inside the subnet cannot access or be accessed from the internet until the proper network configuration is added.

![Image](http://nextwork.ai/sympathetic_brown_vibrant_date/uploads/aws-networks-vpc_157c4219)

### Auto-assigning public IPv4 addresses

I enable auto-assign public IPv4 addresses so that resources, such as EC2 instances, can automatically receive a public IP address when they are launched. This allows them to connect to the internet without assigning a public IP manually.

---

## Internet gateways

### What I did in this step

Connect your VPC to the internet using a internet gateway.

### Setting up internet gateways

Internet gateways are...Internet gateways are key to making applications available on the internet. By attaching an internet gateway, your instances can access the internet and be accessible to external users.

attaching an Internet Gateway to a VPC allows the resources inside the VPC to communicate with the internet. This makes it possible for resources in a public subnet to send and receive internet traffic, as long as the proper route and public IP address are also configured.

![Image](http://nextwork.ai/sympathetic_brown_vibrant_date/uploads/aws-networks-vpc_4ae90410)

---

## Using the AWS CLI

### What I'm doing in this extension

### Exploring CloudShell and CLI

### Debugging my setup

### Comparing CloudShell vs AWS Console

---

---
