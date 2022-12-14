
#  Elastic-Search
<img src="images/1.png">


### What is Elastic Search ?
Elasticsearch is an open source analytics and full-text search engine.It’s often used for enabling search functionality for applications.
<img src="images/2.png">

For example, you might have a blog or a webshop for which you want users to be able to search for various kinds of data. That could be blog posts, 
products, categories, or anything you want. You can build complex search functionality with Elasticsearch, similar to what you see on Google, 
for instance. This includes auto-completion, correcting typos, highlighting matches, handling synonyms,adjusting relevance, etc.
<img src="images/3.png">

Suppose we want to implement searching for a webshop.Besides searching through product names and other full-text fields, we might want to take
a number of factors into account when sorting the results.If the products have ratings, we probably want to boost the relevance of highly rated products.
We also might want to allow users to filter results, such as by price range, brand, size,color, etc., and to sort by price or relevance, for instance.
<img src="images/4.png">

Basically Elasticsearch can do everything you will need to build a powerful search engine,and you will learn all of it in this Git Repository!
Full-text searches is not the only thing Elasticsearch can do, though.You can also query structured data such as numbers and aggregate data, and use Elasticsearch
as an analytics platform.You can write queries that aggregate data and use the results for making pie charts,line charts, or whatever you might need.
Elasticsearch is not really a business intelligence solution, but you can indeed get a lot of valuable information out of the data that you store within Elasticsearch.
<img src="images/6.png">

An example would be to store logs from applications and various server system metrics and then analyze these, perhaps with alerting set up.
You might want to keep track of the number of errors for a web application or the CPU and memory usage of servers, and then show that on a line chart, for instance.
This is referred to as **Application Performance Management - or APM** - and is a quite common use case of Elasticsearch and the Elastic Stack.

Another common thing to do, is to send events to Elasticsearch, which can be anything you want, really. Perhaps we are sending sales from physical stores to Elasticsearch, 
in which case we can analyze which stores sell the most. We can do that with something called aggregations, which you may know from relational databases.
But we can do much more than that, so Elasticsearch is great at analyzing lots of data.

An example of what you can do, is to use machine learning to forecast sales based on historical data. That could also be useful for capacity management.
Perhaps you are keeping track of how many phone calls are made to a support department, and you want to forecast how much staff you will need in the future.
Or perhaps you are keeping track of the number of visitors on a website, and you want to use that to forecast if and when you need to add additional web servers.
<img src="images/7.png">

These were just a couple of examples, so you can of course forecast many other things. Another thing you can do, is **anomality detection**.
If your website normally has 50,000 visitors per day, something is probably wrong if it drops to 5,000, for instance.
Monitoring this can be time consuming, so what you can do instead, is to let machine learning learn the “norm” and let you know when there is an anomality, i.e. when
there is a significant deviation from the normal behavior. This is all done for you, so you don’t have to specify rules, thresholds, etc.
You can then set up alerting for this and be notified whenever something unusual happens, such as receiving an e-mail or a message on Slack.
<img src="images/8.png">

That’s because this way, you really learn the heart of it all and you will then be able to build on top of that knowledge if you need to do other things with Elasticsearch.
Okay, so enough about what you can do with Elasticsearch for now.

### So how does it work?
In Elasticsearch, data is stored as documents, which is just a unit of information. A document in Elasticsearch corresponds to a row in a relational database, and can represent a person, a sale, or anything else you want.
A document then contains fields, which correspond to columns in a relational database.
A document is essentially just a JSON object, so to add a person as a document, you just send a JSON object describing a person to Elasticsearch, such as the example you see below.
<img src="images/9.png">

I will get back to how documents are organized within Elasticsearch soon, and we will also revisit the concept of documents, so just consider this a quick overview. So the way we query documents, is to use a REST API.
<img src="images/10.png">

In case you are not familiar with RESTful APIs, then don’t worry about it at all, as it is just a way of designing HTTP APIs, and you don’t need to be familiar with it at all to use Elasticsearch.

The queries that we send to Elasticsearch are also written in JSON, so the API should be fairly easy to use.

Elasticsearch is written in **Java** and is built on top of **Apache Lucene**.

Elasticsearch has gained a lot of popularity due to its relative ease of use and the fact that it scales extremely well. While Elasticsearch is easy to get started with for simple things, it is still a very complex technology if you want to make use of its full potential. Since Elasticsearch is distributed by nature, it scales very well in terms of increasing data volumes and query throughput. So even if you need to search through millions of documents, searches are still going to be lightning fast!

Elasticsearch is being used by large companies, some of which are MAANG companies .
<img src="images/11.png">

There are many other users of Elasticsearch, and there is a vibrant community, which is a great thing in cases where you need help with something. Elasticsearch is by far the hottest name in terms of search engines, so you definitely made a solid choice when deciding to learn more about it!
