# Database-Instance-Project
 This Project document the process of creating a Database-Instance-Project and connecting MySQL on it.
### Database Creation Method
Selected the "Standard" creation method for the database instance.
Choose the database engine as MySQL. 
Below is the image
![Database engine](/engine_mysql.PNG)

### Database Instance Settings
Configured the database instance identifier with a unique name.
![Database identifier](/db_identifier.PNG)
Set the master username to "admin" and selected "Self-managed" credentials management.
Entered a secure password for the master user and confirmed it.
![master username](/master_username.PNG)

### Instance Configuration
Selected the instance type as db.t2.micro.
![instance type](/instance_type.PNG)
Configured the VPC to use the default VPC, 
Choose the database subnet group as default, 
And Enabled public access to the database instance.
![VPC](/vpc.PNG)
### VPC Security Group
Created a new VPC security group and gave it a unique name.
![VPC Securitygroup](/vpc_securitygroup.PNG)

