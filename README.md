# Lambda Architecture
Inicially came to be in a blog post 2011
http://nathanmarz.com/blog/how-to-beat-the-cap-theorem.html

but the term is utilized only in 2013 by  Marz, Nathan; Warren, James. on Big Data: Principles and best practices of scalable realtime data systems. Manning Publications.

According wikipedia "Lambda architecture is a data-processing architecture designed to handle massive quantities of data by taking advantage of both batch and stream-processing methods"

Margaret Rose on WhatIs.com (https://searchbusinessanalytics.techtarget.com/definition/Lambda-architecture) says "is an approach to big data management that provides access to batch processing and near real-time processing with a hybrid approach." 

The Lambda Architecture is an approach to building stream processing Big Data applications. Created in response to the CAP theorem, which states that it is impossible for a distributed data store in case of a failure to simultaneously guarantees Consistency , Availability and Partition tolerance.

So basically Lambda_Architecture its a workaround of CAP theorem and to do that, its use 2 diferent approaches:

- Batch layer -> bach loads to garantee Consistency.
- Speed layer -> streaming loads to garantee Availability.

these two layers are available for ad-hoc queries on the Serving Layer.


![alt text](http://lambda-architecture.net/img/la-overview_small.png)

Source: http://lambda-architecture.net/










