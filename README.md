# planefinder-spring-data-neo4j

Neo4j was running on debian(docker)

# Neo4j Docker
sudo docker run \
    --publish=7474:7474 \
    --publish=7687:7687 \
    --volume=$HOME/neo4j/data:/data \
    --volume=$HOME/neo4j/logs:/logs \
    --env NEO4J_AUTH=neo4j/password \
    neo4j:latest
just for the test⚠️
