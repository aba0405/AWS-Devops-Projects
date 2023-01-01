# Configuring a static website on Amazon S3

### Topics

1. Step 1: Create a bucket
![image](https://user-images.githubusercontent.com/60788914/210186324-a3cad6bd-a23b-4c79-a69a-188e411f7a20.png)
2. Step 2: Enable static website hosting
-Click Properties
![ClickProperties](https://user-images.githubusercontent.com/60788914/210186391-ef01b0b9-35d8-4688-bd13-e04f173d0000.png)
-Scroll down to enable static website hosting
3. Step 3: Edit Block Public Access settings
-Click permissions tab to clear block all public access
![clickPermissions](https://user-images.githubusercontent.com/60788914/210186426-20c9fd48-811a-4963-ae33-ff9f4ccbb535.png)
4. Step 4: Add a bucket policy that makes your bucket content publicly available
-In the permissions tab, under the bucket policy, choose edit and following policy. This policy will grant public read access to the website
![BucketPolicy](https://user-images.githubusercontent.com/60788914/210186467-79215738-cd58-49c5-8422-5d523937142a.png)
5. Step 5: Configure an index document
-Create a sample index.html file
7. Step 7: Test the website endpoint
-Under Buckets, choose the name of the bucket.
-Choose Properties.
-At the bottom of the page, under Static website hosting, choose the Bucket website endpoint.
-the index document opens in a separate browser window
![Website](https://user-images.githubusercontent.com/60788914/210186566-8330700f-ba39-4d3f-aa05-d8d22669d8a8.png)
