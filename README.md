# Create-and-Manage-Google-Cloud-Resources
This is an exercise originally on Qwiklabs that focuses on creating, managing and deploying resources on Google Cloud

Earn a skill badge by completing the Create and Manage Cloud Resources quest, where you learn how to do the following: Write gcloud commands and use Cloud Shell, create and deploy virtual machines in Compute Engine, run containerized applications on Google Kubernetes Engine, and configure network and HTTP load balancers.

A skill badge is an exclusive digital badge issued by Google Cloud in recognition of your proficiency with Google Cloud products and services and tests your ability to apply your knowledge in an interactive hands-on environment. Complete this skill badge quest, and the final assessment challenge lab, to receive a skill badge that you can share with your network.

--------------------

Challenge scenario
You have started a new role as a Junior Cloud Engineer for Jooli, Inc. You are expected to help manage the infrastructure at Jooli. Common tasks include provisioning resources for projects.

You are expected to have the skills and knowledge for these tasks, so step-by-step guides are not provided.

Some Jooli, Inc. standards you should follow:

Create all resources in the default region or zone, unless otherwise directed.

Naming normally uses the format team-resource; for example, an instance could be named nucleus-webserver1.

Allocate cost-effective resource sizes. Projects are monitored, and excessive resource use will result in the containing project's termination (and possibly yours), so plan carefully. This is the guidance the monitoring team is willing to share: unless directed, use f1-micro for small Linux VMs, and use n1-standard-1 for Windows or other applications, such as Kubernetes nodes.

Your challenge
As soon as you sit down at your desk and open your new laptop, you receive several requests from the Nucleus team. Read through each description, and then create the resources.

Task 1: Create a project jumphost instance
Task 2: Create a Kubernetes service cluster
Task 3: Set up an HTTP load balancer
