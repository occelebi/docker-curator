# docker-curator
Dockerized Elasticsearch Curator 

it runs command daily via crond:
/usr/bin/curator --config ~/curator.yml ~/action_file.yml

Usage:
docker run -d --name {container-name} --link {elastic-search-container-name}:elasticsearch occelebi/curator
