# AWS-Bigdata-Deep-Drive
This repository contains all basic and advance concepts of aws, aws+bigdata.

# VPC

  1. It is a virtual network dedicated to the each AWS account which is logically isolated  from other virtual networks in the cloud.
  2. We can select IP address range, create subnets, and configure route tables, network gateways and security settings through virtual private cloud.
  3. VPC allows the access of resources availabe to the cloud and enables us to launch resources into a virtual network
  4. It is also called netwrorking layer of EC2 instance
  5. VPC is dedicated to each and every AWS account
  
  Subnet:
     -It is a range of IP addresses
     
     -We can launch resources available in AWS account into a specified subnet
     
     -It is also called logical subdivision of an IP network
     
     -Only the communication over the internet, or virtual private gateway connection is possible once have a configuration of subnet with an internet gateway
     -Always use a public subnet for resources that must be connected to the internet, but private subnet is never connected to the internet 
     
     -In order to secure the resources available in AWS, we can put multiple security layers (including network lists and secuirty groups are mentioned)

# Difference between elastic, public and private IP
  
  1. An Elastic IP address is a static IPv4 address designed for dynamic cloud computing
  2. VPC allows the user to select IP address range, create subnets, and configure route tables, network gateways, and security settings. 
  3. IP Addresses • Instances launched in the VPC can have Private, Public and Elastic IP address assigned to it and are properties of ENI (Network Interfaces) 
