This is a small subset of the Elasticsearch datasets that I've used for demos

Settings (replicas, mappings, etc) are found in the .meta file of each set and can be used
for creating your index.

All datasets are in elasticsearch bulk format in the .data file and can be indexed with:

```
curl -s -XPOST localhost:9200/_bulk --data-binary @somedataset.data; echo
```
