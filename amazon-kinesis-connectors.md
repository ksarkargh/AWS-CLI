sudo yum install -y git
git clone https://github.com/awslabs/amazon-kinesis-connectors

change the S3 properties file with Bucket Name 

Add Stream Name

go to /home/ec2-user/amazon-kinesis-connectors/

 mvn clean package
 
cd /home/ec2-user/amazon-kinesis-connectors/samples/target

cd app*/bin

ls

./s3-sample

Go to Bucket and see created resources
https://s3.console.aws.amazon.com/s3/buckets/bigdatacertlabks/?region=us-east-1&tab=overview

Go to Kinesis and sees datas are comming

Also check DynamoDB to See the Shards are Stored into S3

Other Kinesis Library Codes Are:

https://github.com/awslabs/amazon-kinesis-producer

https://github.com/awslabs/amazon-kinesis-agent

https://github.com/awslabs/amazon-kinesis-client

https://aws.amazon.com/blogs/big-data/implementing-efficient-and-reliable-producers-with-the-amazon-kinesis-producer-library/
https://docs.aws.amazon.com/streams/latest/dev/developing-consumers-with-kcl.html

Work Out:
https://www.youtube.com/watch?v=yOFVrHoOgLo
AWS Certification Exams: Kinesis Essentials - Part 1 - 6
