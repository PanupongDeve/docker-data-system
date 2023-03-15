

1. comments volumns neo4j-server in docker compose file

2. sudo mkdir -p neo4j_data

3.  cd neo4j_data
    sudo mkdir -p bitnami
    cd bitnami/
    sudo docker cp <neo4j container>:/bitnami/neo4j .

4.  cd neo4j_data
    sudo mkdir -p opt/bitnami
    cd opt/bitnami/
    sudo docker cp <neo4j container>:/opt/bitnami/neo4j .

5. uncomments volumns neo4j-server in docker compose file
6. sudo docker compose up -d neo4j-server