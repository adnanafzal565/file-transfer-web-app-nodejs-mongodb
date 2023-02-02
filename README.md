# File Transfer Web App (Node JS + Mongo DB) – Express

## Introduction

We have created a project "File transfer web app" we created in Node JS and Mongo DB. It is a file transferring web app that allows you to send files to your colleagues, friends, clients, etc.

## 1. Upload files
You can upload any type of file (image, e-book, executable, iso), the system will NOT prevent you from uploading any certain type of file. Uploaded files are in original quality (no compression is done), and they can be deleted at any time by the uploader.

## 2. Create folders
To organize your files, you can create folders and upload files to that folder. For example, you can create a folder named “College data” and in that folder create further sub-folders “Assignments”, “Thesis”, “Projects” and upload relevant files in each folder separately. You can go for an infinite level of sub-folders, this project can handle that.

## 3. Shareable link (public)
You can share files via a publicly shareable link. Anyone with the link can access your file with or without creating an account. You can also remove the shareable links so they won’t be accessible to the public anymore. There is no expiry time for the shareable link, it will remain accessible as long as it is deleted by the owner.

## 4. Share by E-mail (private)
You can share files via E-mail address if the receiver already has an account in the system. To share files privately, the receiver must have a registered and verified account. Files shared via E-mail will not be accessible by any other person, even if someone tries to get them from the server directory.

## 5. Move files and folders
You can move files from one folder to another with all sub-folders in it. When a file is moved to a new location, all publicly shareable links will lose access to that file. This is another way of removing access to shared links.

## 6. Rename files and folders
The name of the file is automatically set when the file is uploaded, but you can always rename the file. There is no restriction on setting the name of the file, you can even type special characters (!@#$%^*) in it.

## 7. Search
You can search all files and folders uploaded by you or shared by others by their name with you. This allows you to quickly find the files uploaded by you or shared with you by your friends or colleagues.

## 8. Download counts
Files shared via a public link can be downloaded by anyone if he/she has the link. They do not need to register or log in to an account to download that file. While you are logged in can see the number of times that file is downloaded.

## 9. Recycle bin or trash can
When you delete a file, it automatically goes into the recycle bin or trash can. From where you can restore a file if you have deleted it by mistake or you can delete it permanently. Trashed files will not take your space. But when you try to restore it, you must have enough space in your account.

## 10. Backup
Your users will be able to take a backup of all of their files with a single click.

## 11. Business model
You can also make money with this project. You can allow users to upload files up to some GBs for free. After that, you can ask them to pay to upload more data. For example, you can allow users to upload up to 1 GB of files, and put the price of $1 per extra GB. I have added the Stripe and PayPal payment methods that allow you to quickly get money without integrating these payment methods for your convenience.

You just have to change the API keys for Stripe and PayPal and sit back and wait for payments. When someone makes a payment, it will automatically be added to your account and he will automatically get more data to upload. You can allocate a fixed amount from that income to increase your hosting’s hard drives. So your investment in this project will be just $20, which is the price of this project. Future investments will be received from your users.

## 12. Blog integration
Initially, this project was just a file transfer web app. But since you are not restricted to add more features. Now you can share the latest news and articles on your website. Simply go to the admin panel and add blog posts and it will automatically start seeing them on the user side. You can also edit or remove posts from your blog anytime you want.

## 13. Image compression
Now, you can compress your images to reduce their size without losing the quality. When the size is reduced, you will automatically be able to upload more images because you will be using less storage. A test run indicates that an image of 3.2 MB can be reduced to just 890 KB without having to lose too much quality. Check out our tutorial on image compression in Node JS.

## 14. Security
Your files will not be accessible by any person other than you or the people you have shared with. Even if someone finds the directory where you have stored all your files, he will still be unable to list or view the files.

## 15. Data volume
There is no limit on the volume of data uploaded in this system. You can upload as much larger files as your server allows, and you can upload as many files as needed. You can also create infinite levels of folders and sub-folders.

## Installation

- Download and Install Node JS and Mongo DB

- Start Mongo DB server by running the following command in "bin" folder where Mongo DB is installed:
    ```
    ./mongod
    ```
    or
    ```
    mongod
    ```

- Then open command prompt in this folder and run the following command:
    ```
    > npm update
    > npm install -g nodemon
    > nodemon server.js
    ```

- Then open your browser and enter the following address:
    ```
    http://localhost:3000/
    ```

If you face any problem, please feel free to contact us.