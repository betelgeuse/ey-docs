# Introduction to Instances on AppCloud

Instances on AppCloud comprise of the compute resources that are dedicated to running
your Ruby application in the cloud.  Instances can be configured to serve your 
application tier, database tier, cache tier, background processing and utilities, 
and more.  On AppCloud, instances are available in a handful of size configurations to 
meet your cpu, memory, and disk space needs.  


## Topics

* ### [[Instance types & roles on AppCloud|instance-types]]
  Learn more about the different types of instances and their roles on AppCloud.

* ### [[Instance sizes available for your environments|instance-sizes]]
  Learn more about the varying instance sizes available on AppCloud.
  
* ### [[Change an Instance size|instance-change-size]]
  Learn how to change an instances size within your AppCloud environment.
  
* ### [[Frozen instances on AppCloud|instance-frozen]]
  Learn how to deal with frozen or crashed instances on AppCloud.

* ### [[Degraded instances on AppCloud|instance-degraded]]
  Learn how to replace a degraded instance on AppCloud.

## Persistent Storage
Your application code and database are written out to **persistent storage** 
volumes on AppCloud. We automatically mount these volumes and take backups for you.

Both the `/data` mount on the application master instance and the `/db` mount on the database 
master instance(s) are persistent. We take advantage of Amazon's EBS storage allowing us to 
take regular disk snapshots of both of these volumes. 

If you ever have to rebuild your instances from scratch you will have the ability to restore 
both of these volumes from previous snapshots.