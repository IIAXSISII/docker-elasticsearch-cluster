# Docker Based Elasticsearch Cluster With Kibana

This repo contains docker based elasticsearch cluster (kibana and elasticsearch) that can be run as single node locally without any additional changes. In order to run the project, you will need docker and docker-compose installed locally. Run the command docker-compose up -d to stand up the Kibana at 5601 port and elasticsearch at 9200 port. 
By design the cluster does not have security or ssl enabled. If you wish to install security or add ssl, you will need to make changes to the configs to add certs and enable security. Primary purpose of this repo was to be able to start elasticserach in single node mode locally for development purpose.
If you wish to add security, feel free to raise a PR.

ElasticSearch URL: `http://localhost:9200`

Kibana URL: `http://localhost:5601`
