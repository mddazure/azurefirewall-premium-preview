# Azure Firewall Premium Demo 

This demo is an adaptation of the demo released for the 20Q3 private preview.

A demo sequence and script are provided in the Powerpoint deck in this repo.

The policy deployed through FirewallPolicy.template.json maps to the demo sequence in the Powerpoint deck.

Topology deployed through FirewallTopology2.template.json:

![image](azurefirewallpremium_demo_setup.png)

NB: the template does not include the Web App. This should be in place already. Prior to running the demo verify if the Web App still exists and deploy manually if not.

The following template samples files are included:
1. FirewallTopology1.template.json – This is the main template file which include the deployment definition of this 
premium firewall preview in single VNet topology
2. FirewallTopology2.template.json – This is the main template file which include the deployment definition of this 
premium firewall preview in spoke to spoke topology
3. FirewallPolicy.template.json – This is Azure Firewall Policy configuration parameters definition
4. CACertificate.template.json – This is a template for easy deployment of customer CA certificate in Key vault.

Refer to the pdf document in this repo for deployment instructions.



