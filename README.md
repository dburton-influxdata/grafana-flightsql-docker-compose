# grafana-flightsql-docker-compose
Docker Compose file with FlightSQL Plugin and Data source

Goal:
Build a Grafana Docker container with the FlightSQL plugin installed and a predefined FlightSQL Data source. 
You need to customize the FlightSQL datasource yaml configuratoin file with the host/cluster URL, the tokens and the database/bucket name.

The yaml files should be saved in the provisioning directory and mounted as a volume in the Docker container. This will load it into Grafana on startup.

For multiple databases, you can create a seperate yaml file to have them included. 
