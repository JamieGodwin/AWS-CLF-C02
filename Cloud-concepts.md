### Cloud computing is on demand delivery of compute power, database storage, and other applications. 
## Prvate cloud
- Used by a single organisation, not the public. 
- Complete control.
- More secure.
## Public cloud
- Cloud resources owned and operated by third party.
## Hybrid cloud
- Some servers private and some on the cloud.

## 5 cloud characteristics
- On demand self service.
- Broad network access.
- Multiple users can use the same infastructure.
- Rapid elasticity and scalability.
- Measured service; Pay for what you use

## 6 advantages of cloud computing
- Less CapEx and more OpEx
- Reduced prices due to AWS scalability
- Scale based on usage
- Increased speed and agility
- Go global quickly

## Types of cloud computing
### Infastructure as a service (IaaS)
- Building blocks for cloud IT
- Highest flexibility

### Platform as a service (Paas)
- No need to manage underlying infastructure
- Focus on deployment and management 

### Software as a service (SaaS)
- Completed product run and managed by the company (Like gmail)

## AWS global infastructure
### AWS regions
- Compliance: Countries my have rules on where data can be stored, so you would launch in that country.
- If most users will be in one country, it makes sense to launch the app there.
- Not all region have the same services.

### Availability zones
- Usually min is 3, max is 6.
- They are seperate data centres
- This allows for high availability, because if one centre goes down, you can still be working in the other zones. 
- They're connected with high bandwidth and low latency.

### AWS edge locations
- They catch the data sent out by availability zones, improve it then send it again to the user. 

## Shared responsibility model
### AWS's Responsibilities
- AWS is responsible for the security "of" the cloud. This includes protecting the infrastructure that runs all of the services offered in the AWS Cloud. 
- Responsibilities include hardware, software, networking, and facilities that run AWS Cloud services.

### Customer's Responsibilities
- Customers are responsible for the security "in" the cloud. This means customers are responsible for securing their data and applications that they run on the AWS infrastructure. 
- Responsibilities include managing the guest operating system, firewall configuration, and data encryption, as well as ensuring access control and identity management.
### Shared Controls
- Some areas, like patch management and configuration management, are shared controls. AWS provides the tools, but customers are responsible for using these tools to manage their applications and data.