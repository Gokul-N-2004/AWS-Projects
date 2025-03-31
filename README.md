# *First Project: URL-Shortener*

### Project Structure :
 → s3-bucket  → index.html  → style.css  → script.js  → lambda.py  → /lambda-function  → /api-gateway  

### Architecture :
![Image](https://github.com/user-attachments/assets/befa34e5-606d-4de8-8892-25386d8f3075)
### Output :
![Image](https://github.com/user-attachments/assets/bd45a6ae-d998-4b51-9702-7f6f852b64dc)

_________________________________________________________________________________________________

# *Second Project: SNS-Event-Notification*

### Project Structure:
SNS-Topic ➝ Lambda-Function ➝ S3-Bucket

### Architecture :
![Image](https://github.com/user-attachments/assets/887a9690-f7cb-4ed2-aa2c-fe2bb84c9743)
### Output :
![Image](https://github.com/user-attachments/assets/2d84c30c-c8e5-41e8-9ab3-85b65549c1b8)

___________________________________________________________________________________________________

# *Third Project: VPC-NAT Gateway*

### Project Structure:
VPC  
├── Public Subnet   
│   → Bastion Host (EC2)  
│   → Internet Gateway (IGW)  
│   → Route Table (Public)  
│   → Routes to IGW   
├── Private Subnet  
│   → Private EC2 Instance  
│   → NAT Gateway (For Internet Access)  
│   → Route Table (Private)  
│   → Routes to NAT Gateway  
└── Security Groups  
    → Bastion Host SG (Allows SSH from the internet)  
    → Private EC2 SG (Allows SSH only from Bastion Host)  


