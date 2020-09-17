# Learning cloud

## VPC - Virtual Private Cloud

*Amazon Virtual Private Cloud (Amazon VPC) enables you to launch AWS resources into a virtual network that you've defined. This virtual network closely resembles a traditional network that you'd operate in your own data center, with the benefits of using the scalable infrastructure of AWS.*

#### Key Concepts
- **VPC** - A virtual network dedicated to the AWS account
- **Subnet** - The range of IP-addreses in the VPC
- **Route Table** - The set of rules which says where the network traffic is directed
- **Internet Gateway** - The gateway attached to the VPC which enables communication to the internet


#### Lessons from the guide
- By default, an instance in a nondefault VPC is not assigned a public IPv4-address
- Elastic IP (EIP) is a static IPv4-address designed for dynamic cloud computing

## EC2 - Elastic Compute Cloud

*Amazon Elastic Compute Cloud (Amazon EC2) provides scalable computing capacity in the Amazon Web Services (AWS) cloud. Using Amazon EC2 eliminates your need to invest in hardware up front, so you can develop and deploy applications faster. You can use Amazon EC2 to launch as many or as few virtual servers as you need, configure security and networking, and manage storage. Amazon EC2 enables you to scale up or down to handle changes in requirements or spikes in popularity, reducing your need to forecast traffic.*

#### Key Concepts
- Provides virtual computing environments, known as instances
- Comes with preconfigured templates known as AMI (Amazon Machine Images). Basically OS + software
- Secure login using keypairs (.pem files)
- Persistant storage with Amazon Elstaic Block Store (Amazon EBS)

