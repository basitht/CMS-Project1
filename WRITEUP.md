
Azure App Service
App Service is a managed service for hosting web apps, mobile app back ends, RESTful APIs, or automated business processes. Azure App Service is a fully managed "Platform as a Service" (PaaS) that integrates Microsoft Azure Websites, Mobile Services, and BizTalk Services into a single service, adding new capabilities that enable integration with on-premises or cloud systems. Azure App Service gives users several capabilities.
	1.Provision and deploy Web and Mobile Apps in seconds
	2.Build engaging iOS, Android, and Windows apps
	3.Automate business processes with a visual design experience
	4.Integrate with "Software as a Service" (SaaS) applications (Office 365, Salesforce, Dynamics, OneDrive, Box, Dropbox, Twilio, Twitter, Facebook, Marketo, and so on) and on-premises applications

Virtual Machine
Virtual machines deploy and manage VMs inside an Azure virtual network. An Azure VM gives you the flexibility of virtualization without having to buy and maintain the physical hardware that runs it. However, you still need to maintain the VM by performing tasks, such as configuring, patching, and installing the software that runs on it.
	1. Development and test – Azure VMs offer a quick and easy way to create a computer with specific configurations required to code and test an application.
	2. Applications in the cloud – Because demand for your application can fluctuate, it might make economic sense to run it on a VM in Azure. You pay for extra VMs when you need them and shut them down when you don’t.
	3. Extended datacenter – Virtual machines in an Azure virtual network can easily be connected to your organization’s network.
 
I successfully deployed my app using the App Service. I choose Azure App Service for following reasons:

1.Azure VMs are more expensive to run in comparison to Azure App Service.

2.Azure App Service requires much less managerial efforts in comparison to Azure Virtual Machines.

3.The development of app is much simpler and faster in Azure App Service.

4.Azure App service takes away some of the additional responsibilities of customer, and gives it back to cloud provider, for which customer is responsible while working with Azure VMs.

Pricing comparison between App service & Virtual Machine

***********************************************************************************************
Resources	  Price	                     Plan
***********************************************************************************************
App service	*  Monthly cost           *
                *  $54.75	          *   B1: 1 core(s), 1.75 GB RAM, 10 GB storage, $0.075
***********************************************************************************************
Virtual Machine	*  Monthly cost
                *   $152.62               *    Pay as you go
***********************************************************************************************




