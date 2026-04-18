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


## 📸 Screenshots

### EC2 Instance Running
![EC2](screenshots/Screenshot%202026-04-18%20125914.png)

### Security Group Creation
![SG](screenshots/Screenshot%202026-04-18%20130036.png)

### Subnet Details
![Subnet](screenshots/Screenshot%202026-04-18%20130839.png)

### Instance Launch
![Launch](screenshots/Screenshot%202026-04-18%20131111.png)

### CLI Output
![CLI](screenshots/Screenshot%202026-04-18%20131134.png)

### SSH Login
![SSH](screenshots/Screenshot%202026-04-18%20131150.png)

### Additional View
![Extra](screenshots/Screenshot%202026-04-18%20131213.png)
