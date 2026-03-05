# AWS Static Website Hosting using Amazon S3 & CloudFront

## Project Overview

This project demonstrates how to host a static website using Amazon Web Services. The website files are stored in an Amazon S3 bucket and delivered globally using Amazon CloudFront as a Content Delivery Network (CDN).

The website is built using HTML, CSS, and JavaScript and can be accessed through the CloudFront distribution endpoint.

---

## Technologies Used

* Amazon S3
* Amazon CloudFront
* HTML
* CSS
* JavaScript

---

## Deployment Steps

1. Created an Amazon S3 bucket to store the website files.
2. Uploaded all static website files including HTML, CSS, images, and vendor assets.
3. Enabled Static Website Hosting in the S3 bucket.
4. Configured a bucket policy to allow public read access.
5. Created a CloudFront distribution for faster global content delivery.
6. Set `index.html` as the default root object in CloudFront.
7. Verified the deployment using the CloudFront endpoint URL.

---

## CloudFront Endpoint

https://dzf6emikv4l5q.cloudfront.net

---

## Screenshots

All the steps involved in the deployment process are captured in the screenshots section. These screenshots include:

* S3 bucket creation and file upload
* Static website hosting configuration
* Bucket policy configuration
* CloudFront distribution setup
* Final working website

---

## Project Structure

```
project-folder
│
├── index.html
├── css/
├── img/
├── vendor/
└── README.md
```

---

## Author

Vivek Desai
MCA Student | Cloud Computing Enthusiast
