Answers to Udacity's Questions :

1. How did changing values on the SparkSession property parameters affect the throughput and latency of the data?
I would like to say  processedRowsPerSecond is effecting performance the most in a positive way.

2. What were the 2-3 most efficient SparkSession property key/value pairs? Through testing multiple variations on values, how can you tell these were the most optimal? 
To make the performance better, I would maximize the processedRowsPerSecond as I mentioned in the first Question. 
The most optimal pairs are “spark.default.parallelism” and “spark.sql.shuffle.partitions”. 