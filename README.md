# Azure Firewall Premium 20Q3 
In this private preview release, the entire service configuration and deployment can be done only via ARM (Azure 
Resource Manager) templates.
The template is a JavaScript Object Notation (JSON) file that defines the infrastructure and configuration for your 
project. The template uses declarative syntax, which lets you state what you intend to deploy without having to write 
the sequence of programming commands to create it. In the template, you specify the resources to deploy and the 
properties for those resources.
To allow quick deployment of this Azure Firewall Premium Private Preview edition, a set of samples templates are 
available for download here.
The following template samples files are available in this shared folder:
1. FirewallTopology1.template.json – This is the main template file which include the deployment definition of this 
premium firewall preview in single VNet topology
2. FirewallTopology2.template.json – This is the main template file which include the deployment definition of this 
premium firewall preview in spoke to spoke topology
3. FirewallPolicy.template.json – This is Azure Firewall Policy configuration parameters definition
4. CACertificate.template.json – This is a template for easy deployment of customer CA certificate in Key vault.

Refer to the pdf document in this repo.