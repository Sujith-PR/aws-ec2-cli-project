# AWS EC2 Launch using CLI 🚀

## 📌 Project Overview
Launched an Ubuntu EC2 instance using AWS CLI instead of the console to understand real-world infrastructure provisioning.

## ⚙️ Steps Performed

1. Configured AWS CLI
2. Fetched latest Ubuntu AMI
3. Created Security Group and allowed SSH (port 22)
4. Selected default subnet
5. Launched EC2 instance using CLI

## 💻 Command Used

```bash
aws ec2 run-instances \
  --image-id ami-0ec10929233384c7f \
  --instance-type t3.micro \
  --key-name aws-project2 \
  --security-group-ids sg-xxxxxxxx \
  --subnet-id subnet-xxxxxxxx
