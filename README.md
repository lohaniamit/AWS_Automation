# AWS_Automation
How to automate AWS Endorsement

### EC2 :
Done:
1. Create your own Key based SnapShots 
2. Delete SnapShots 
3. Delete/ Terminate any EC2 instance which does not have a user/ any specific tag 
4. stop any useless Running Ec2 instance

### RDS : 
Planned:
1. delete RDS Instance
2. Delete RDS Cluster
3. Stop any useless Running RDS Cluster/Instance
4. Delete useless Snapshots 
5. Delete any RDS Instance or Cluster which does not have a specific tag with it 
6. Delete any RDS Snapshot that is older then 2 days 

This bunch of Scripts can directly be used with AWS lambda function for Automation purposes as well
