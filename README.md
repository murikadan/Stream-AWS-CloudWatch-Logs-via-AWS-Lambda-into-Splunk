# Stream-AWS-CloudWatch-Logs-via-AWS-Lambda-into-Splunk

Cloudformation template and lambda function to 
	1. Enable VPC Flow logs and write flow logs to Cloudwatch 
	2. Lambda function which subscribes to Cloudwatch and pushes these logs to Splunk HEC

To configure multiple VPC's, provision stacks with same template, by passing different vpc id's.

References:
	https://www.splunk.com/blog/2017/02/03/how-to-easily-stream-aws-cloudwatch-logs-to-splunk.html
	https://www.splunk.com/blog/2016/11/29/announcing-new-aws-lambda-blueprints-for-splunk.html
