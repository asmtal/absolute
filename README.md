DOCUMENTATION TO DESCRIBE FRAMEWORK
This explains the framework for deploying the new project "Absolute Agent web service".

Steps

1. Provision s3 bucket in aws using terraform 

2. Connect my s3 bucket to on-premise Kubenetes cluster using direct connect

3. Use terraform module to creates AWS CloudFront with for customer access

4. configure security framework to protect s3 bucket
   
5. configure cloudFront distribution using terraform
