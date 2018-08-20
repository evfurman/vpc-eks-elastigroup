*This template is provided by Spotinst to construct a basic VPC Network, EKS Cluster, and a Spotinst Elastigroup for the nodes*

I have customized several parts of the base template for my own purposes. These include:

* Peering to existing Production and NonProduction VPCs
* Utilizing existing DHCP Option Sets for Production and NonProduction
* Reconfiguring existing Route Tables to access EKS VPCs
* Attaching EKS VPCs to existing R53 Private Hosted Zones
* Joining EKS Nodes to SimpleAD server in UserData
* Adding a shutdown script to deregister EKS Nodes 
