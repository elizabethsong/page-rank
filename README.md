# page-rank
PageRank algorithm for search

Create search engine for Lawfare Blog. There are two datasets available: 'small.csv.gz' is a smaller, example graph from "Deeper Inside Pagerank" research paper and 'lawfareblog.csv.gz' is the main file to test on.

To run:
```
$ python3 pagerank.py --data=./lawfareblog.csv.gz --search_query='corona'
```
Alternatively, run make_personalization_vector function to filter and search.

To run:
```
$ python3 pagerank.py --data=./lawfareblog.csv.gz --filter_ratio=0.2 --personalization_vector_query='corona'
```
