# AWS EC2 Commands

This repository stores commonly used AWS CLI commands to launch EC2 instances quickly using the AWS CLI.

## 🔹 Launch EC2 Instance

Use the following command to launch a new EC2 instance:

```bash
aws ec2 run-instances \
  --image-id ami-xxxxxxxxxxxxxxxxx \
  --count 1 \
  --instance-type t2.micro \
  --key-name MyKeyPair \
  --security-group-ids sg-903004f8 \
  --subnet-id subnet-6e7f829e
