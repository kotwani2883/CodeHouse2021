# CodeHouse2021

### Team Boolean Autocrats

Ppt link : https://drive.google.com/file/d/1YDvrN9IED6bYbiYJ4KmmPsvf12OSVkw-/view

#### Prodcut : SD-WAN is the application of software-based network technologies to WAN connections to provide
high-performance, cost-effective access to cloud services, private data centers, and SaaS-based
enterprise applications. SD-WAN solutions replace traditional WAN routers to provide dynamic,
policy-based traffic delivery across many WAN connections. SD-WAN technology includes service
gateways and orchestrators.


### Steps to be followed : 
* Web Scrapping : Used Instant Web Scrapper (KInda Extensioin used)
This can also be replaced using the Beautiful Soup which is basically a Python library used for extracting data from the Html and Xml web pages.
For Web scrapping we used the gartner Report which contains list of reviews made by the customers for both the CISCO Sd-WAN as well as Vmware SD-wan
* Data Preprocessing
Before raw data could be sent through a machine learning model it has to undergo preprocessing. And it’s simply because data in the real world are generally Incomplete, Noisy and Inconsistent. And if this is fed into the machine learning model, results can come unexpectedly! And that’s not really what we want. Data preprocessing is a proven method for resolving such issues.


#### Steps in Data Preprocessing
* Gathering the data
* Import the dataset & Libraries
* Divide the dataset into Dependent & Independent variable
* Check for missing values
* Check for Categorical values
* Split the dataset into training and test set
* Feature Scaling

![image](https://user-images.githubusercontent.com/56580582/180375672-d791eadb-ad34-441a-9786-c5d2dc1fb53e.png)

SENTIMENTAL ANALYSIS
We use TextBlob package to carry out the sentiment analysis of the reviews. As TextBlob itself
has only 60% of working efficiency, We clean the data and use only the relevant tokens with
appropriate tags to carry out the sentiment analysis which gives us better results.

DataVisualization : It is done using tthe seaborn and matlpotlib library
