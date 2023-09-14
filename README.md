# 10WeeksofCloudOps-ChallengeWeek1
Host a static website on AWS or Azure or GCP and implement CICD
Hosting Your Website on Amazon S3
Step 1: Create an Amazon S3 Bucket

Log in to your AWS Management Console.
Navigate to the Amazon S3 service.
Click on the "Create bucket" button.
Choose a unique name for your bucket (e.g., my-portfolio-website).
Select the AWS region that's geographically closest to your target audience.
Leave the default settings for public access control.
Step 2: Upload Your Website Files

Inside your S3 bucket, click on the "Upload" button.
Select all the files and folders for your website.
Upload them to the bucket.
Step 3: Configure S3 Bucket for Static Website Hosting

Go to the bucket properties.
In the "Static website hosting" section, click on "Edit."
Choose the "Use this bucket to host a website" option.
Set the "Index document" to your main HTML file (e.g., index.html).
Optionally, set the "Error document" to your error page (e.g., error.html).
Click "Save changes."
Wait for CloudFront Distribution to Deploy

It may take some time for your CloudFront distribution to deploy. You can check its status in the CloudFront console.

