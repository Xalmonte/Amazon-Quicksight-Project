# Amazon-Quicksight-Project
## Steps to visualize data on Amazon Quicksight
- An AWS account with permissions to create S3 buckets and create a Amazon Quicksight Account
- Download a dataset of 50,000 best-selling Amazon products
- Store dataset into an Amazon s3 bucket
- Connect the s3 bucket with Quicksight and create visualizations

## Setup Instructions
1. Go into Amazon console and select S3
2. Create new bucket and give it a name (I used xavier-amazon-project)
3. Keep default settings and select create bucket at the bottom
4. Select the bucket that you just created and upload your csv file then select create
5. Once again click on the S3 bucket and upload your JSON file and select create
6. You should now have 2 objects in your S3 bucket and you are ready to move on to the next phase of the project
7. Click on the Amazon console and navigate to Quicksight
8. If you don't have a Quicksight account, set up an enterprise edition (Please cancel subsciption before 30 days so you're not getting charged)
9. While setting up, please include a Quicksight account name and an email address
10. At the bottom, under S3, select your bucket (In my case, xavier-amazon-project bucket will be selected) then select finish
11. Once your account has been successfully created (this can take a few minutes), click go into Quicksight
12. Select datasets and select create new dataset
13. Select S3
14. Give your data source a name and in another tab, paste the URL of your S3 bucket under the JSON object (Pictured below on where to get URL), and click connect
15. Select Visualize, on the next pop up, select Interactive sheet and select create
16. You should now see a blank graph with different category fields on the left
17. Drag and drop a field in which you want to see visualized
18. You can sort in Ascending or Descending order
19. Congratulations! You have now completed the project.
