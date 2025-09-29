Version: v1
#
#This scrpit will report AWS resources usage
#
#################
set -x
# AWS S3
# AWS EC2
# AWS LAMBDA
# AWS IAM Users
#
#
#list s3 bucket
echo "print list of s3 buckets"
aws s3 ls

# list EC2 Instances
echo "print list of ec2 instances"
aws ec2 describe-instances

# list AWS Lambda instances
echo "print list pf lambda functions"
aws lambda list-functions

#list Aws IAM Users
echo "print list of iam users"
aws iam list-users
