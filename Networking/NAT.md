## 🛠️ AWS Architecture With NAT Gateway Integration
AWS Architecture with NAT Gateway helps private subnet resources access the internet securely.

- 🌐 Public subnet has a NAT Gateway connected to an Elastic IP.

- 🔁 Private subnet sends internet traffic through the NAT Gateway.

- 🔒 This allows private resources to access the internet (e.g., for updates) without being exposed to the internet directly

### 🧩 Components
---
- 🏗️ **VPC** – A VPC (Virtual Private Cloud) is an isolated network environment in AWS
- 📦 **Subnets** – Subnets are parts of a VPC where where we can place AWS resources like EC2 instances.
- 🌍 **Internet Gateway** – An Internet Gateway allows resources in a VPC, like EC2 instances, to connect to the internet.
- 🗺️ **Route Table** – A Route Table contains rules that decide how network traffic is directed within a VPC.
- 🛡️ **Security Group** - A Security Group acts like a virtual firewall that controls inbound and outbound traffic for your AWS resources.

- 🔁 **NAT Gateway** - A NAT Gateway is used to provide secure internet access to resources in a private subnet.
- 📬 **Elastic IP** - An Elastic IP is a static public IP address in AWS that you can assign to your cloud resources, like EC2 instances.


## 🖼️ Diagram
![AWS Architecture](/aws-architecture/NAT-Gateway.svg)

