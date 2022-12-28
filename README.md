# Youtube-Data-Analysis-using-AWS
This repo contains the project on Cloud for Youtube Data Analysis using AWS services.


-----------------
Business overview
-----------------

YouTube is a global online video sharing and social media platform headquartered in San Bruno, California. It was launched on February 14, 2005, by Steve Chen, Chad Hurley, and Jawed Karim. 
It is owned by Google, and is the second most visited website, after Google Search. YouTube has more than 2.5 billion monthly users who collectively watch    more than one billion hours of videos each day. 
It offers paid content such as movies and exclusive content produced by YouTube.
Video categories on YouTube include music videos, video clips, news, short films, feature films, documentaries, audio recordings, movie trailers, teasers, live streams, vlogs, and more. 
YouTube has had an unprecedented social impact, influencing popular culture, internet trends, and creating multimillionaire celebrities.
Most content is generated by individuals, including collaborations between YouTubers and corporate sponsors.


------------
AWS overview
------------
Amazon Web Services, Inc. (AWS) is a subsidiary of Amazon that provides on-demand cloud computing platforms and APIs to individuals, companies, and governments, on a metered, pay-as-you-go basis. This cloud computing web services provider provides various services related to networking, compute, storage, middleware, IOT and other processing capacity, as well as software tools. This frees clients from managing, scaling, and patching hardware and operating systems.

AWS services are delivered to customers via a network of AWS server farms located throughout the world. Fees are based on a combination of usage (known as a "Pay-as-you-go" model), hardware, operating system, software, or networking features chosen by the subscriber required availability, redundancy, security, and service options.

AWS's virtual computers emulate most of the attributes of a real computer, including hardware central processing units (CPUs) and graphics processing units (GPUs) for processing; local/RAM memory; hard-disk/SSD storage; a choice of operating systems; networking; and pre-loaded application software such as web servers, databases, and customer relationship management (CRM).


-------
Project
-------

Approach

-   Load youtube INPUT dataset in AWS S3

-   Read INPUT datasets from S3 using jupyter notebook in AWS Glue - PySpark

-   Apply transformation on the input data to extract and load the required fields from input data for further analysis

-   Convert INPUT data from JSON and CSV to parquet for better performance.

-   Read from parquet dataset and perform data analysis.


-------------
Data Analysis
-------------

-   Analyze most liked, disliked,commented video along with channel name and respective count

-   Analyze category-wise most liked video along with channel name

-   Analyze top 5 most liked categories

-   Analyze top 5 most disliked categories

-   Analyze top 5 most commented categories

-   Second or third category of most liked (rank, dense rank function)

-   List the same-day trending videos with most likes

-   Find top liked channel

-   Find top liked category

-   List top videos with over 50k or 1 Lk comment

-   Find the top channel names in each category, with most number of videos

-   List the top 5 videos went trending the most no. of times

--------------
Applied logics
--------------
--> Reading and writing data to S3

--> Grouping and aggregations

--> Data partitioning

--> Window functions

--> Date-time manipulation

--> Broadcast Join


----------
Tech Stack
----------
➔ Language: Python3 

➔ MPP Computing Engine : Spark

➔ Services: AWS S3 , AWS Glue , AWS Athena , IAM - User, Roles, Policies
