FROM neo4j:3.4.1

VOLUME /var/lib/neo4j/data

ENV APOC_URI https://github.com/neo4j-contrib/neo4j-apoc-procedures/releases/download/3.4.0.1/apoc-3.4.0.1-all.jar

RUN wget $APOC_URI && mv apoc-3.4.0.1-all.jar plugins/apoc-3.4.0.1-all.jar

EXPOSE 7474 1337 7687
