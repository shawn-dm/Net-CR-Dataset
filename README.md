# Net-CR-Dataset
To conduct research on Cantonese rumor detection based on graph convolutional networks, we construct a Cantonese rumor dataset with the graph structure information, which contains 2,419 source tweets, 112,539 retweets, and 92,260 replies, totaling 207,218 nodes and 202,437 edges. 

We get these data from Twitter.

## source_tweet.csv
It contains the information of source tweets, including tweet ID (id), tweet text (full_text) and tweet label (label).

The tweet with a label of '1' is annotated as a rumor. Otherwise, a non-rumor.

## edges.csv
It contains the graph structure information of retweets/replies, including tweet ID (tweet_id) and their parent ID (parent_id).


