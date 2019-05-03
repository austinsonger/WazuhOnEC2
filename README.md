# WazuhOnEC2
Push Button Deployment of Wazuh on EC2 using CloudFormation.

Wazuh is an open-source detection system. The aim of this project is to make deployment of Wazuh a single click automated process.

- PreRequisites:
You have AWS Command Line Interface installed on your system.
The Deploy.sh and EC2_Wazuh.json files are both present in the same directory.
A KeyPair is generated beforehand on AWS and its name is updated in "Default" field
under Parameters block in EC2_Wazuh.json file.

- Instruction to Deploy:
Run the Deploy.sh script to deploy Wazuh on AWS EC2 Instance running Ubuntu 18.

- The deployment defaults are:
Instance Type: T2 micro
OS: Ubuntu Server 18
KeyName: EC2 Wazuh
Allowed SSH Locations: All
These values can be changed as needed in the Parameters block in EC2_Wazuh.json
file.
