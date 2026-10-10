# streaming-workshop

## Running the services

Start the workshop stack with `docker compose up -d`. The services use the
Docker host network so Flink can reach Redpanda and Postgres in environments
where container-to-container bridge networking is unavailable. Kafka and
Postgres are available at `localhost:9092` and `localhost:5432`; open the Flink
UI at <http://localhost:18081>.