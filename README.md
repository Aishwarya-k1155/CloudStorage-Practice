# CloudStorage-Practice
Practice task for creating an S3 bucket, uploading a file, and testing accessibility using AWS Cloud Storage.

# CloudStorage-Practice

## Objective
The main goal of this task was to get hands-on experience with cloud object storage. I wanted to learn how to create a storage bucket in AWS S3, upload a file, and check if it can be accessed properly.

## Tools I Used
- AWS Free Tier account
- AWS S3 (Simple Storage Service)
- Web browser to test file access

## What I Did

1. **Created a Free AWS Account**  
   I first signed up for the AWS Free Tier so I could practice without worrying about any costs.

2. **Created a New S3 Bucket**  
   I went to the S3 service in AWS and clicked **Create bucket**. I gave my bucket a unique name, `aishwarya-task-2025`, and selected the **US East (N. Virginia) region**. I left **Block Public Access** as default because I wanted to keep it secure.

3. **Uploaded a Sample Image File**  
   I uploaded a **small image file** to the bucket to test storing objects in S3. This was the main file I needed to show for the task.

4. **Checked Access Control List (ACL)**  
   I explored the **ACL options** to see if I could make the file public. ACLs are used to control **who can access a file**. By default, only I (the bucket owner) have full access. I noticed the option to make the file public was **disabled** because AWS blocks public access by default. This helped me understand how AWS **prioritizes security** for buckets and files.

5. **Used a Presigned URL**  
   Since I couldn’t make the file public through ACL, I created a **presigned URL**. This allowed me to **temporarily access my private image file** in the browser. I set it to expire in 1 hour for safety. When I opened the URL, my image loaded perfectly.

6. **Took a Screenshot**  
   Finally, I took a **screenshot showing my image displayed in the browser** via the presigned URL. This proves the file was uploaded successfully and could be accessed.

## Screenshot
![Uploaded File](screenshot.png)

## What I Learned
- Learned how **AWS S3 buckets store objects** and control access.
- Explored **ACLs** and understood why public access can be restricted.
- Learned to use **presigned URLs** as a safe way to share private files temporarily.
- Gained hands-on experience in **uploading files, managing access, and verifying accessibility** in the cloud.

