# Amazon-Quicksight-Project
## Steps to visualize data on Amazon Quicksight
- An AWS account with permissions to create S3 buckets and create a Amazon Quicksight Account
- Download a dataset of 50,000 best-selling Amazon products
- Store dataset into an Amazon s3 bucket
- Connect the s3 bucket with Quicksight and create visualizations

## Setup Instructions

1. Go into Amazon console and select S3
   
   <img width="1437" alt="S3 console" src="https://github.com/Xalmonte/Amazon-Quicksight-Project/assets/169603464/cc293d8a-c1c9-424a-a33b-f1441e7d7845">/

2. Create new bucket and give it a name (I used xavier-amazon-project)

<img width="1437" alt="Name Bucket" src="https://github.com/Xalmonte/Amazon-Quicksight-Project/assets/169603464/7dd38f38-23da-4bcb-a4ce-baf53bd886c5">

   
3. Keep default settings and select create bucket at the bottom

 <img width="1437" alt="Create Bucket" src="https://github.com/Xalmonte/Amazon-Quicksight-Project/assets/169603464/438d25fc-19aa-4088-90ec-f671b012af9e">

4. Select the bucket that you just created and upload your csv file then select upload

<img width="1438" alt="Upload Dataset CSV" src="https://github.com/Xalmonte/Amazon-Quicksight-Project/assets/169603464/70643348-2c04-4aa8-a6b4-281223f678a4">

   
5. Once again click on the S3 bucket and upload your JSON file and select upload

<img width="1438" alt="Upload JSON file" src="https://github.com/Xalmonte/Amazon-Quicksight-Project/assets/169603464/6021f840-7df1-43f1-91cc-f8c46599f82f">

   
6. You should now have 2 objects in your S3 bucket and you are ready to move on to the next phase of the project

   <img width="1438" alt="Object List" src="https://github.com/Xalmonte/Amazon-Quicksight-Project/assets/169603464/44434305-f2db-4729-be32-5997a13ed8d8">

7. Click on the Amazon console and navigate to Quicksight 
8. If you don't have a Quicksight account, set up an enterprise edition (Please cancel subsciption before 30 days so you're not getting charged)
9. While setting up, please include a Quicksight account name and an email address
10. At the bottom, under S3, select your bucket (In my case, xavier-amazon-project bucket will be selected) then select finish
11. Once your account has been successfully created (this can take a few minutes), click go into Quicksight
12. Select datasets and select create new dataset

    <img width="1438" alt="New Dataset" src="https://github.com/Xalmonte/Amazon-Quicksight-Project/assets/169603464/bd2ddb56-80d2-4f47-8cf0-dd09684dc5a1">

13. Select S3
    
14. Give your data source a name and in another tab, paste the URL of your S3 bucket under the JSON object (Pictured below on where to get URL), and click connect

  <img width="1438" alt="S3 URL" src="https://github.com/Xalmonte/Amazon-Quicksight-Project/assets/169603464/9a9126ee-d7de-4b8f-a242-832194f6b01e">

15. Select Visualize
    
<img width="1438" alt="Visualize SS" src="https://github.com/Xalmonte/Amazon-Quicksight-Project/assets/169603464/a483e08c-6c7e-41f2-a4a8-1b8bd29ebf26">

16. on the next pop up, select Interactive sheet and select create

<img width="1438" alt="Interactive Sheet SS" src="https://github.com/Xalmonte/Amazon-Quicksight-Project/assets/169603464/508f0c16-3c3e-47cf-9527-d332ca48e819">


17. You should now see a blank graph with different category fields on the left. Drag and drop a field in which you want to see visualized (like the example pictured below)

<img width="1437" alt="Quicksight Graph" src="https://github.com/Xalmonte/Amazon-Quicksight-Project/assets/169603464/b7e5e656-d107-443e-9bf3-0a8cbe794bfa">

18. Feel free to play with it as you can sort by Ascending/Descending order, different graph types, etc.
    
19. Congratulations! You have now completed the project.
