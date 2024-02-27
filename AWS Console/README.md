Solution Implementation using AWS Console
Follow the below implementation steps one by one to implement this architecture in AWS:

Purchase a Domain Name or Use an existing domain.
Create Public Hosted Zone (Optional — External Domains)
Create S3 Buckets for the root domain and the sub-domain.
Upload Website Content to Sub-domain S3 Bucket.
Set up Root Domain for Website Redirect
Request a Public Certificate from ACM
Set up CloudFront Distribution for Sub Domain
Set up CloudFront Distribution for Root Domain
Route DNS traffic for your domain to your CloudFront distribution (Route 53 or External DNS Provider)
Testing Website Root & Sub-Domain
Creating a Code Pipeline for CI/CD
Testing the CodePipeline
Clean Up


