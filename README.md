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
[http://localhost:3000/connections/datasources/new](http://localhost:3000/connections/datasources/new)
![image](https://github.com/user-attachments/assets/feb15253-6a6d-4855-b465-753c3a0b9f72)
paste http://prometheus:9090 then click 'Save & test'
![image](https://github.com/user-attachments/assets/f9824bef-c1ca-4a5e-8cad-d5a81f4338df)


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
