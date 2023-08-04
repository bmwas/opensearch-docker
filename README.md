# opensearch-docker
A small repository with opensearch (docker-compose) installation files. Opensearch is the open source version of elasticsearch -  https://opensearch.org

## Might have to send this on terminal otherwise you get memory error issues
sysctl vm.max_map_count=262144

## Print all documents in a specific index on browser

http://localhost:9200/yc/_search?pretty=true&q=*:*
or
http://192.168.122.1:9200/yc/_search?pretty=true&q=*.*

## Visualize indices
http://192.168.1.21:9200/_cat/indices
