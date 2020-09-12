# page-rank
PageRank algorithm for search

Create search engine, with 'small.csv.gz' which is an example graph from "Deeper Inside Pagerank" research paper.

To run:
```
$ python3 pagerank.py --data=./lawfareblog.csv.gz --search_query='corona'
```
Alternatively, run make_personalization_vector function to filter and search.

To run:
```
$ python3 pagerank.py --data=./lawfareblog.csv.gz --filter_ratio=0.2 --personalization_vector_query='corona'
```
