Project: Deploy Static Website on AWS  
Student: Anthony Proctor  
Submission Date: April 24, 2025  

Website URL (S3 Endpoint):  
http://udacity-anthonyproctor-bucket.s3-website-us-east-1.amazonaws.com/

CloudFront Distribution URL:  
https://d1a0vrqacyu8u6.cloudfront.net/index.html

Project Description:  
This project demonstrates how to deploy a static website on AWS using the following services:
- **Amazon S3** for hosting the website files (HTML, CSS, JavaScript)
- **IAM Policies** to securely configure access permissions
- **Amazon CloudFront** to improve delivery speed and reduce latency via a CDN

Steps Completed:
1. Created an S3 bucket named `udacity-anthonyproctor-bucket` in the `us-east-1` region.
2. Enabled static website hosting on the bucket and configured the index and error documents.
3. Applied a bucket policy to allow public access to the website content.
4. Uploaded all website files (HTML, CSS, JS) to the bucket.
5. Configured a CloudFront distribution to serve the site content with improved performance and global availability.
6. Verified that the website is accessible through both the S3 website endpoint and the CloudFront distribution.

Screenshots:  
The following screenshots are included in the submission zip folder:
- S3 Bucket Creation Confirmation  
- Static Website Hosting Settings  
- IAM Policy Attached  
- Files Uploaded to Bucket  
- CloudFront Distribution Settings  
- Website Viewed in Browser via CloudFront URL  

Note: All AWS resources used in this project will be deleted after the project is reviewed and passes to avoid unnecessary charges.

Thank you for reviewing my submission!

Anthony Proctor  
anthonyproctor@gmail.com
