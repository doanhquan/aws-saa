# IAM: User and group
  - IAM stands for identity and access management, is a global service
  - Root account created by default, shouldn't used and shared
  - User are people within your organization, and can be grouped
    - ex: we have six people, each of half of them work together so we have two groups
  - Groups only contain users, not other groups
  - User don't have to belong to groups, can belong to multiple groups
# IAM: Permission
  - Users or Groups can be assigned JSON documents called policies, ex:
    - ![image](https://github.com/doanhquan/aws-saa/assets/62228094/b6aefa91-721e-45fb-a30d-59fa7eaabcef)
    - So it looks just like this, what a user is allowed to do or what a group
      - we can see that we allow people to use the EC2 to service and do describe on it, to use the elastic load balancing service and cloudwatch service with some permissions
  - These policies define the permissions of the users
  - In AWS you apply the least privilege principle: don’t give more permissions than a user needs 

