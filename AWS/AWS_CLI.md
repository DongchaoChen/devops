# AWS CLI quick reference

## AWS EC2 
### Volume
- Create Volume
  * create 100GB volume
    ```
    aws ec2 create-volume --size 100 --region en-west-1 --availability-zone eu-west-1b --volume-type gp2
    ```
  * TBD

## AWS S3
- get size of files in S3 bucket 
  ```
  aws s3 ls S3://<folder> --human-readable
  ```
  
  
  