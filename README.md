# airflow-with-spark-iceberg

This project integrates Apache Airflow with Apache Spark and Apache Iceberg to create a robust data pipeline.

## Project Structure

- `dags/`: Contains Airflow DAGs.
  - `my_dag.py`: Example DAG for orchestrating tasks.
- `jobs/`: Contains Spark jobs.
  - `count_permits.py`: Spark job to count permits.
  - `ingest_permits.py`: Spark job to ingest permits.
- `notebooks/`: Jupyter notebooks for data exploration and analysis.
- `spark/`: Contains Spark-related configurations and Dockerfile.
  - `Dockerfile`: Dockerfile for setting up Spark environment.
- `warehouse/`: Data warehouse directory.
- `docker-compose.yml`: Docker Compose file to set up the development environment.
- `LICENSE`: Project license.
- `README.md`: Project documentation.

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone <repository-url>
   cd airflow-with-spark-iceberg

2. **Start the development environment:**

Access Airflow UI: Open your browser and go to http://localhost:8090.

## License
This project is licensed under the terms of the LICENSE.