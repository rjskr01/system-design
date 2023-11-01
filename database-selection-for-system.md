# Database selection
## Need to consider the following factors while selecting the data base

1. Structure of data (very structured data or totally non structured data and semi structured data)
2. Query pattern 
3. Amount of scale


# Caching Solutions

Mostly caching will be stored as key value format

## Use case for caching

1. To Query the database a lot of times , we could cache the value in cache
2. Making a call different service and it having high enough latency, we want to cache the response at our local system.

## Solutions for caching 
1. Redis - Recommended , Most Stable and Popular
2. Memcached
3. etcd 

# File Storage
1. Blob Storage - Example Amazone S3 , Which used to store images , videos and documents like PDF etc.,
2. Content Delivery Network (CDN) - Mostly used to store the same images which used in different geographical locations 

# Search Content
1. Text search Engine - Example Elastic Search and Solr search - Both of these are implemented over the top of Apache Lucene 
2. Fuzzy search - if we provide the search with typo mistake it will identify the exact word and provide appropriate results

# Metrics Tracking System
1. Graphite
2. Grafana
3. Promethus 

These are time series database can be name Open TSDB

# Data warehouse 
  dumping multiple data's it's used for offline reporting purpose not transactional purpose 
  