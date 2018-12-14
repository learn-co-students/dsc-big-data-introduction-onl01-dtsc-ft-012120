
# Introduction to Big Data 

## Introduction

In the information age, data in huge quantities has become available to analysts and decision makers. Big data Analytics involves dealing with data that is big in __volume__ and high in __variety__ and __velocity__, making it challenging for data scientists to run their routine analysis activities. Due to the a vast increase in the amount of such data in recent times, A number of specialized platforms and development paradigms have been developed to fulfill this need. Using such specialist approaches allow data scientists to gain valuable insights from such complex data, ranging from daily transactions to customer interactions and social network data.

Big Data Analytics is the application of advanced analytics techniques on big data. This section aims to focus on some of the different analytical approaches and tools which can be applied to big data to gain valuable insights to aid business decision making. 

## Objectives
You will be able to:
- Understand and explain how big data differs from routine data that is routinely analyzed
- Describe 3 V's of big data as attributes that differentiate big data
- Evaluate big data technologies and application areas for Big Data Analytics

## What is Big Data

The topic of "Big Data" has received a lot of hype lately, accompanied by huge amount interest from big businesses as it can potentially provide them data driven decision making abilities. Big data is one of the most discussed topics in business today across industry sectors, although it was barely known a few years ago. This lesson will focus on what big data is, why it is important, and the benefits it brings. 


<img src="bd5.png" width=600>


Big data is no different than normal data that we have seen so far , its only Bigger. This changes the analytical landscape as the huge increase in size of the data required specialist tools, techniques and platforms, big data analytics deals with. It helps us solve new problems and find improved ways for old problems. 



### Defining Big Data

Despite of all the hype around this topic, there is no clear consensus on __How to define Big Data__ . The term often gets related to Business Analytics and Data mining for identifying relationships and associations present in huge amounts of transaction data.  

In the data science domain, Big Data usually refers to datasets that grow so large that they become awkward to work with using traditional database management systems and analytical approaches. They are data sets whose size is beyond the ability of commonly used software tools and storage systems to capture, store, manage, as well as process the data within a tolerable elapsed time.

#### How Big is the Big Data ?

Big data sizes are constantly increasing, currently ranging from a few terabytes (TB) to many petabytes (PB) of data in a single data set. Consequently, some of the difficulties related to big data include capture, storage, search, sharing, analytics, and visualizing. Today, enterprises are exploring large volumes of highly detailed
data so as to discover facts they didn’t know before. The sources of data that companies usually deal with along with their application areas are highlighted in the image below:

<img src="size2.png" width=600>

Here are some of the examples of big data:
- Web data. Customer level web behaviour data such as page views, searches, reading reviews, purchasing, can be captured. 
- Text data (email, news, Facebook feeds, documents, etc) is one of the biggest and most widely applicable types of big data. 
- Time and location data. GPS and mobile phone as well as Wi-Fi connection makes time and location information a growing source of data. 
- Smart grid and sensor data. Sensor data are collected nowadays from cars, oil pipes, windmill turbines, and they  are collected in extremely high frequency. Sensor data provides powerful information on the performance of engines and machinery. 
- Social network data. Within social network sites like Facebook, LinkedIn, Instagram, it is possible to do link analysis to uncover the network of a given user. 


## 3 V's of Big Data 

Three main features characterize big data: volume, variety, and velocity, or the three V’s. The volume of the data is its size, and  how enormous it is. Velocity refers to the rate with which data is changing, or how
often it is created. Finally, variety includes the different formats and types of data, as well as the different kinds of uses and ways of analyzing the data

<img src="3v.jpg" width=500>

Let's look at what these 3Vs refer to.


### VOLUME
Volume refers to the __amount of data__ generated through websites, portals and online applications in a data driven business. Especially for online retailers, volume encompasses the available data that are out there and need to be assessed for relevance. 

Consider the following:

<img src="users.png" width=500>

Facebook has 2 billion users, Youtube: 1.5 billion users, Twitter: ~400 million users and Instagram 700 million users. Every day, these users contribute to billions of images, posts, videos, tweets etc. You can now imagine the insanely large amount (or Volume) of data that is generated every minute and every hour.  

Data volume is the primary attribute of big data. Big data can be quantified by size in TBs or PBs, as well as even the number of records, transactions, tables, or files. Additionally, one of the things that make big data really big is that it’s coming from a greater variety of sources than ever before, including logs, clickstreams, and social media as we will see below. 


### VELOCITY
Velocity refers to the speed with which data is generated. Staying with our social media example, every day 900 million photos are uploaded on Facebook, 500 million tweets are posted on Twitter, 0.4 million hours of video are uploaded on Youtube and 3.5 billion searches are performed in Google. This is like a nuclear data explosion. 

Following image shows an idea around what happens on major social media platforms in one minute . 

<img src="var.png" width=500>

SO velocity is basically the frequency of data generation or the frequency of data delivery. The leading edge of
big data is streaming data, which is collected in real-time from the websites

Big Data helps the company to hold this explosion in velocity, accept the incoming flow of data and at the same time process it fast so that it does not create bottlenecks.

### VARIETY

Variety in Big Data refers to all the structured and unstructured data that has the possibility of getting generated either by humans or by machines. The most commonly added data are structured -texts, tweets, pictures & videos. 

In addition to above,  unstructured data like emails, voice mails, hand-written text, ECG reading, audio recordings etc, are also important elements under Variety. Variety is all about the ability to classify the incoming data into various categories.


<img src="unstruct.jpg" width=500>

This leads us to the most widely used definition in the industry by Gatner.


### *Big data is high-volume, high-velocity and/or high-variety information assets that demand cost-effective, innovative forms of information processing that enable enhanced insight, decision making, and process automation*.

All of the above are examples for 3Vs are sources of Big Data, no matter how you define it.

**NOTE**: *Some researchers have discussed the addition of a fourth V, or __Veracity__. Veracity focuses on the quality of the data. This characterizes big data quality as good, bad, or undefined due to data inconsistency, incompleteness, ambiguity, latency, deception, and approximations*

The key takeaway here is that the “Big” in big data is not just about volume. 
> You are not only getting a lot of data. It is also coming at you fast, it is coming at you in complex format, and it is coming at you from a variety of sources.

It is also important to point out that there might not be too much value in defining an absolute threshold for what constitutes big data. Today’s big data may not be tomorrow’s big data as technologies evolve. It is more of  a relative concept. From anyone’s given perspective, if your organization is facing significant challenges (and opportunities) around data’s volume, velocity and variety, it is your big data challenge. Typically, these challenges introduce the need for distinct data management and delivery technologies and techniques.

## Big Data Analytics

With the evolution of technology and the increased amounts of data as shown above, the need for faster and more efficient ways of analyzing such data has also grown exponentially. Having Big data __alone__ is no longer enough to make efficient decisions at the right time. As we mentioned above, Big Data can not be easily analyzed with traditional data management and analysis techniques and infrastructures. Therefore, there arises a need for new
tools and methods specialized for big data analytics, as well as the required architectures for storing and managing such data. Accordingly, the emergence of big data has an effect on everything from the data itself and its collection, analysis , visualization , to the final extracted decisions.

The image below shows the technology stack showing key tools and platforms heavily being employed in big data analytics today. 



<img src="stack.jpg" width=800>


Explaining each one of these tools/platforms etc. is outside the scope of this lesson. You are, however, encouraged to look up these technologies and see their role in big data analytics. Such a stack maps the different big data storage, management, analytics tools/methods, visualization and evaluation tools to the different phases of the decision making process. 

Based on above, the key activities associated with big data analytics are reflected in three main areas: 

- Big data storage, warehousing and distribution
- Big data computational platforms
- Big data analyses, visualization and evaluation

Such framework can be applied for knowledge discovery and informed decision making in big data driven organizations.

### Example Business Applications of Big Data Analytics

Along with some of the most common advanced data analytics methods such as regression analysis, association rules, clustering, classification and decision trees, some additional analyses have become common with big data.

For example, social media has recently become important for social networking and content sharing. Yet, the content that is generated from social media websites is enormous and remains largely unexploited. However, social media analytics can be used to analyze such data and extract useful information and predictions 

<img src="sna.png" width=500>

>__Social media analytics__ is based on developing and evaluating informatics frameworks and
tools in order to collect, monitor, summarize, analyze, as well as visualize social media
data. 

Social media analytics facilitates understanding the reactions and conversations between people in online communities, as well as extracting useful patterns and intelligence from their interactions, in addition to what they share on social media websites.

On the other hand, __Text Mining__ and __NLP__ techniques are used to analyze a document or set of documents in order to understand the content within and the meaning of the information contained. Text mining has become very important nowadays since most of the information stored, not including audio, video, and images, consists of text - in form on emails, sms, social media feeds, blogs etc. While data mining deals with structured data, text presents special characteristics which basically follows a non-relational form.

<img src="nlp.jpg" width=500>

__Sentiment Analysis/Opinion Mining__, is also becoming more and more important as online opinion data, such as blogs, product reviews, forums, and social data from social media sites like Twitter and Facebook, grow tremendously. 

>__Sentiment Analysis__ focuses on analyzing and understanding emotions from subjective text patterns, and is enabled through text mining. It identifies opinions and attitudes of individuals towards certain topics, and is useful in classifying viewpoints as positive or negative. 

<img src="senti.png" width=600>

Sentiment analysis uses NLP and text analytics in order to identify and extract information by finding words that are indicative of a sentiment, as well as relationships between words, so that sentiments can be accurately identified

Another potentially growing big data analytics option is __Advanced Data Visualization (ADV)__ and __Visual Analytics (VA)__. Presenting information so that people can consume it effectively is a key challenge that needs to be met, in order for decision makers to be able to properly analyze data in a way to lead to concrete actions.
<img src="viz.jpg" width=800>

And finally, one of the leading application in big data analytics is __Recommendation Systems__. Powerful recommendation engines can be built for anything from movies and videos to music, books, and products as offered by Netflix, Pandora, or Amazon. As customers of an online retailer browse through products, the Recommendation system offers recommendations of products they might be interested in. In our daily online browsing and shopping routine, most of us often come across messages like the one shown below. That's a recommendation system doing it's job. 

<img src="rec.png" width=800>



Regardless of business or consumer the perspective, Recommendation systems have been immensely beneficial. Big data is the driving force behind Recommendation systems. A typical Recommendation system cannot do its job without sufficient data and big data supplies plenty of user data such as past purchases, browsing history, and feedback for the Recommendation systems to provide relevant and effective recommendations. In a nutshell, even the most advanced Recommenders cannot be effective without big data.

### So what's next ?

After this quick introduction, we will look at Map-Reduce, a distributed computation platform designed to incorporate big data analytics and how it is used by Hadoop/Apache Spark development environments to analyze Big data. 

## Additional Reading 

Big Data is a huge subject and incorporates a lot of underlying technologies and principles. You are advised to visit following resources and also read around good Bid data articles to develop a sound and holistic understanding of the domain. 

- [Youtube: Big Data Trap](https://www.youtube.com/watch?v=0cizsKDn3TI) - Highly recommended, an excellent lecture on the social dimension of big data.

- [Big Data vs Data Science](https://www.educba.com/big-data-vs-data-science/) - How to relate big data analytics to routine analytics that we have so far !

- [Big Data Analytics](https://pdfs.semanticscholar.org/d392/0f02dbb15da19b04d782fc0546ef113e0bf7.pdf) - A great paper summarizing big data related terms, ideas etc. 


## Summary 

In this introductory lesson on big data, we looked at what data qualifies at "Big Data". We looked at how it is hard to come up with a standard definition of Big Data due to the variety of its applications and use cases. 3V's is a standard way of describing big data and deals with key attributes such datasets. 
