Create an S3 Bucket for Static Website Hosting

Steps to Create and Configure an S3 Bucket
1. Log in to AWS Management Console
Go to AWS Console.

2.Search for S3 service and open it.

3. Create a New Bucket
Click Create bucket.
Bucket name: Enter a name (mybucket name-my.home.page.bucket).
Region: Choose your preferred AWS region.
Uncheck "Block all public access" under Object Ownership → ACLs enabled and Permissions.

5. Configure Public Access
In Bucket permissions, uncheck "Block all public access".
Acknowledge the warning.Click Create bucket.

6. Enable Static Website Hosting
Open your newly created bucket.
Go to the Properties tab.Scroll down to Static website hosting.
Click Edit.Select Enable.Choose "Host a static website".

Set:Index document: index.html(i used pro.html)Click Save changes.

7. Upload Your Website Files,Go to the Objects tab.
Click Upload → Add files → select your files to upload (I uploaded pro.html,pro.css,pro.js,bgimg.jpg).Click Upload.

8. Access Your Website
Go back to Properties → Static website hosting.
Copy the Bucket website endpoint URL.Open it in your browser — your static site is live

