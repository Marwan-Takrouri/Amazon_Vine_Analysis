# Amazon_Vine_Analysis
***Purpose and Overview ***

For this project I am partnering with Jennifer, an account manager at Big Market. SellBy, my client, loves to talk about the power of big data, but Jennifer isn't a data expert. So i started off the project by giving her a quick overview of what big data
Jennifer knows that this project has outgrown Excel, SQL, and other databases we have used before. This means that am getting to explore brand-new tools and think about data in a whole new way. To begin, I decided to explore the technologies that support the big data ecosystem. This way i can decide what technologies I  will need to answer SellBy's questions and help Jennifer.
Now that I trained Jennifer and Jennifer have an understanding of big data, the next step is figuring out how to process it. 
Since my work with Jennifer on the SellBy project was so successful, I ’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. 


The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.In this project, I ’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. 
Next, I used  PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholder

***Results ***

I have picked the wireless products Big data to be analysed and the out come was as below  :


Total counts of votes was 72587

![Alt text](https://github.com/Marwan-Takrouri/Amazon_Vine_Analysis/blob/main/total%20reviews.png)
Total Helpful Votes of 65581
![Alt text]()

Total Vine members Votes 613
![Alt text](https://github.com/Marwan-Takrouri/Amazon_Vine_Analysis/blob/main/vine%20reviews.png)

Total non Vine members 64968
![Alt text](https://github.com/Marwan-Takrouri/Amazon_Vine_Analysis/blob/main/vine-no.png)

Total 5 Stars Reviews 30765
![Alt text]()

Total 5 stars Reviews paid 222
![Alt text]()

Total 5 Stars reviews non paid 30543
![Alt text]()

Percentage of paid 5 star reviews 0.007%
![Alt text](https://github.com/Marwan-Takrouri/Amazon_Vine_Analysis/blob/main/total%20reviews.png)

Percentage of paid 5 star reviews 99%
![Alt text]()

5 start reviews compared to paid is 36% with vine 
![Alt text]()

5 start reviews compared to paid is 47 % no  vine 
![Alt text]()



***Summary ***

In my opinion , the outcome of the analysis of the wireless products reviews is not biased at all taking consideration all the above data analysis , 
One more aspect could be developed is finding the remaining of the 5 starts review compared to non paid reviews of the whole population , but this needs to be collected from another data source .as we built our data analysis on one source which is the AWS data file ,I think for the integrity of the analysis we need to have the same exercise repeated from two to three different sources .









