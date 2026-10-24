# AWS VPC Peering Project

## Project Overview
This project demonstrates private communication between two AWS Virtual Private Clouds (VPCs) using VPC Peering.

## Architecture
- VPC 1 CIDR: `10.0.0.0/16`
- VPC 2 CIDR: `10.200.0.0/16`
- VPC 1 contains a public subnet and a private subnet.
- VPC 2 contains a private subnet.
- Three EC2 instances are deployed across the subnets.

## Configuration
- Created a VPC Peering connection.
- Configured route tables for communication between VPCs.
- Configured security groups for required traffic.

## Testing
Connectivity was tested from the private EC2 instance in VPC 1 to the private EC2 instance in VPC 2 using ping.

**Result:** 4 packets received, 0% packet loss.

## AWS Services Used
- Amazon VPC
- Amazon EC2
- VPC Peering
- Route Tables
- Security Groups

