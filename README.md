# Country Search Engine
Basically main moto beyond to create these project is always try to take better result for searching about anything which you want regards the country without any difficulties. A search engine built to retrieve geographical information of any country within limited time span and aslo acquire to get better result.

# Crawling 
Apache Nutch is used to crawl the relevant web pages from the 50 seed URL's given.

# Indexing 
Apache Solr is used to index the crawled web pages. The default page rank model of indexing using Solr gives satisfactory results. The results are further improved by implementing and applying HITS algorithm.

# User Interface
The results obtained using different indexing methods, different clustering methods and different query expansion methods are compared with the results obtained on the same query using Google and Bing.

# Clutering
Both flat clutering (K-means) as well as hierarchical clustering (single-link) is used to group similar web pages together and improve search results.

# Query Expansion
Associative metric and scalar clustering are used to get the new modified enhanced expanded query to improve search results. 

For more information on the search engine refer "Project Report.pdf"
