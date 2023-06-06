# Running apache airflow 2.6.1 in docker.
Here are the steps to take to get airflow 2.6.1 running with docker on your machine.
https://airflow.apache.org/docs/apache-airflow/stable/howto/docker-compose/index.html
## Create dags, logs and plugins folder inside the project directory
```
mkdir ./dags ./logs ./plugins
```

## Launch airflow by docker-compose
```
docker-compose up -d
```

## Check the running containers
```
docker ps
```


Open browser and type http://localhost:8080 to launch the airflow webserver

