# Deploy Static Website on AWS

The static project deployed is located at the /projec-deployed folder

The files included are: 

index.html - The Index document for the website.
/img - The background image file for the website.
/vendor - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
/css - CSS files for the website.

The following are the screenshot steps require to deploy a static website on AWS using S3 and Cloudfront.

## S3 Bucket
[S3 bucket](/screenshots/s3bucket.png?raw=true "S3 Bucket")

## Website Files
![S3 bucket](/screenshots/s3bucket_detail.png?raw=true "Website files")

## Static Hosting
![S3 bucket](/screenshots/s3bucket_static_web_hosting.png?raw=true "Static Hosting")

## Static IAM Policy
![S3 bucket](/screenshots/s3bucket_iam_policy.png?raw=true "IAM Policy")

## Website Distribution
![S3 bucket](/screenshots/s3_bucket_cloudfront.png?raw=true "Cloudfront")


## Web Browser Access

https://my-588592539415-bucket.s3.amazonaws.com/index.html

http://my-588592539415-bucket.s3-website-us-east-1.amazonaws.com/

https://d1icblw9n22trz.cloudfront.net/index.html