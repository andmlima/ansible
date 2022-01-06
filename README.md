# VPC - create VPC in AWS by Ansible playbook
## Playbook vpc-setup.yml has the tasks: 
 Import VPC Variables

 Create vprofile VPC
 
 create Public Subnet 1 in Zone1

 create Public subnet 2 in zone2
 
 create Public subnet 3 in zone3
 
 create Private Subnet 1 in Zone1
 
 create Private subnet 2 in zone2
 
 create Private subnet 3 in zone3
 
 Internet Gateway Setup
 
 Set up public subnet route table
 
 Nat gateway and allocate new EIP if a nat gateway does not yet exist in the subnet.		
 
 Set up Private subnet route table
 
 Create variables file for vpc output	
	
#Playbook bastion-instance.yml has the tasks:
 
 Setup Vprofile Bastion Host
 
 Import VPC setup Variable
 
 Import VPC setup Variable
 
 Create vprofile ec2 key
 
 Save private key into file bastion-key.pem
 
 Create Sec Grp for bastion host
 
 Provisioning Bastion Host		


