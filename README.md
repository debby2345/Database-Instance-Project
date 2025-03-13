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

### Storage Configuration
Selected the storage type as General Purpose (SSD).
Allocated 20 GB of storage.
Enabled storage autoscaling with a maximum storage threshold of 1000 GB.
![Storage](/storage_type.PNG)

### Database Authentication and Additional Configuration
Selected password authentication as the database authentication method.
![database Authentication](/db_authentication.PNG)
Configured the database options, including the database name.
Used the default database parameter group and option group.
![dbname](/db_name.PNG)
Enabled automated backups with a backup retention period of 1 day.
Selected "No preference" for the backup window.
![db backup](/db_backup.PNG)


