# Monitor PostgreSQL With Prometheus and Grafana

[A basic tutorial to follow from original author, Reza; 
](https://rezakhademix.medium.com/a-complete-guide-to-monitor-postgresql-with-prometheus-and-grafana-5611af229882)

## Requirements
* Install Docker

## Use the following command to run
* Run `docker compose up -d` (If you installed makefile you can use `make up`)


## You'll be able to monitor  
* CRUD operations on database
* Locks & Dead Locks
* Connections
* CPU Usage
* Load Average
* Memory Usage
* Shared Buffers
* Current Fetched Data
* Database Cache
* Parallel Workers
* Transactions
* Sessions
  

## Ports
The containers and their exposed ports are:

-   **postgresql** - `:5432`
-   **prometheus** - `:9090`
-   **grafana** - `:3000`
-   **postgresql-exporter** - `:9187`


