# Airflow in Docker

## Installation
Follow Airflow's documentation of [Running Airflow in Docker](https://airflow.apache.org/docs/apache-airflow/stable/howto/docker-compose/index.html) to get Airflow up

## Commands to use

- To initialise the database

```docker compose up airflow-init```

- Cleaning-up the environment

```docker compose down -v```

- Running Airflow

```docker compose up```

## Accessing the web interface
Once the cluster has started up, you can log in to the web interface and begin experimenting with DAGs.

The webserver is available at: http://localhost:8080. The default account has the login `airflow` and the password `airflow`.

