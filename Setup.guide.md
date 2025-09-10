
🔹 Step 1: Create RDS (MySQL)
=
1.Go to AWS Console → RDS → Create Database.

2.Engine = MySQL (or Aurora MySQL).

3.Deployment = Standard.

4.Templates = Free tier (if testing).

5.Set:

    * DB name = javacode-rds-project
    *Master username = admin
    *Password = Admin123456
    *Connectivity:

6.VPC = same VPC where your EC2 will be launched.

     *Public Access = No (best practice, keep private). 
     *Security group: create/select one (we’ll edit later).
     *Create database → wait for Available.

👉 Note the RDS endpoint (example: javacode-rds-project.cb0y2csmwusj.ap-south-1.rds.amazonaws.com).
![image_alt]()
