# cc22-assign1

This was a fun assignment; I'm glad that the assignments in this class are based on real world tasks. 

# Steps I took to complete this assignment:

1. First I had to create an S3 bucket as my IAM user. I did this in the AWS console, and essentially followed the steps we did in class. I logged into the console > service/S3 > create bucket > configured the buckt (named it && allowed public access). After this I just finished setting up the bucket; enabled static website hosting, set the index page to index.html, and edit the bucket policy, just like we did in class with the policy generator. 

2. The second part was actually the most time consuming for me, and that was "building the website". I don't have any experience working on the front end of a website, so it was interesting to learn a little about html and css. I essentially went online, found some html + css skeletons, and adopted them to my website. I repeated this process to make all the html files, including index.html. This is where I link the other pages in the navigaiton bar, add the two pictures, the video, and formatted the home page. 

3. After I had constructed the website, I upload the files to the bucket, and this git. Now, with the link to the bucket you could access the website, navigate to the other 5 pages (which haven't been fleshed out at the moment), and view the pictures/video. 

4. The last step was to setup CloudFront for the website, which is argueably the easiest part of this assignment. All I had to do was go to services > CloudFront, create a new distribution, and enter the origin domain (for which I put the link to the bucket endpoint, the link to the website.) 

## Has Been Taken Down ##
Link to Website: http://cc22-assign1.s3-website-us-east-1.amazonaws.com
