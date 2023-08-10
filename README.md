# grafana-flightsql-docker-compose
Docker Compose file with FlightSQL Plugin and Data source

#### Goal:
Spin up a Grafana Docker container with the FlightSQL plugin installed and a predefined FlightSQL data source. 
Customize the FlightSQL datasource yaml configuratoin file with the host/cluster URL, the tokens and the database/bucket name.

The yaml files should be saved in the datasources directory as it will be mounted as a volume in the Docker container. This gets loaded it into Grafana during startup.

For multiple databases, you can create a seperate yaml file to have them included.

1. Review and edit the docker-compose.yaml file
2. Edit the datasources/flightsql.yaml file for your cluster and database settings
3. run docker compose up
