# vlogCw2Kh
VPC Flow log data move to kinesis firehose by cloudwatch event

vlogCw2Kh -> vlogKh2S3 -> vlogS32Es

1. vlogCw2Kh
   - VPC flow log data move to s3 by cloudwatch event
2. vlogKh2S3
   - Kinesis firehose data transformation csv file to S3
3. vlogS32ES
   - S3 data read and take geoip move elastic search
