# mongodb-performance-workshop
Follow on to mongodb-intro-workshop.

Discuss mongodb performance.  

Indexes: think about trees, size, in-memory vs disk, number of indexes, query planner.  

Sorting. In memory vs indexed.  
https://www.mongodb.com/docs/manual/tutorial/sort-results-with-indexes/?jmp=university

Using explain().  

Take a large dataset and query it in optimal and non-optimal ways. Show the effects of different indexes. Discuss the importance of 

Collection design: document ref / sub document, memory vs disk, cache. Think about the client and query patterns. Ideal scenario is the most common queries return a single document or a small set of data from multiple documents with a single query (as opposed to requiring multiple searches / lookups).  

Memory memory memory - Mongo loves it! Hot indexes must be in memory. 

Use some of the lessons from this;
https://university.mongodb.com/mercury/M201
