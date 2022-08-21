## SonarQube Deployement using Cloudformation Stack over EC2 and AWS RDS

SonarQube Version 9.0.1.46107

AWS PostgreSQL Version 11

AWS Instance t2.Medium
RDSCluster:
      MasterUsername: "sonaradminuser"
      MasterUserPassword: "sonaradminuserdatabase#123"
      DBClusterIdentifier: "sonaradmindb"
      Engine: aurora-postgresql
      EngineMode: provisioned
      DatabaseName: "sonaradmindb"
      DBInstanceClass: db.t3.medium
      
SSD Storage 25GB

![image](https://user-images.githubusercontent.com/84206636/130907905-aa6514ed-5dd7-4106-b933-75ab6db8d0a7.png)
![image](https://user-images.githubusercontent.com/84206636/130908009-c4aa55c6-d377-46fd-be4c-a9672ea2d7bd.png)




