# Neo4j Nginx for Bloom Security Headers
This example shows how to configure Nginx to proxy forward to Bloom and add in additional headers.
The proxy/default.conf shows how to add the additional headers.
The neo4j.conf in the docker container uses the MacOS host name. 

Instructions
------------ 

Build the Nginx docker image
1) cd to proxy directory
2) run `docker build -t reverseproxy`

Launch the docker container(s)
`docker-compose -f docker-compose.512_single_enterprise_bloom_nginx.yml up`

