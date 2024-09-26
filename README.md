# postgre-prometheus-grafana
## run
```bash
sudo docker compose up --build
```

## database access
```bash
sudo docker exec -it postgres psql -U example
```

## configure data source


## grafana
[http://localhost:3000/](http://localhost:3000/)

## prometheus
[http://localhost:9090/](http://localhost:9090/)

## exporter
[http://localhost:9187/](http://localhost:9187/)

## clean-up
```bash
sudo docker system prune -a --volumes
```