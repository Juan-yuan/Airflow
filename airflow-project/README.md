# Airflow
## Install Apache Airflow with Docker:
  1. Create a folder materials in your Documents
  2. put file: docker-compose.yaml in above folder and fill in the configurations
  3. create a .env file, put values:
    AIRFLOW_IMAGE_NAME=apache/airflow:2.4.2
    AIRFLOW_UID=50000
  4. run: docker-compose up -d
  5. go to: localhost:8080
  6. debugging: 
    * check details: docker-compose ps
    * remove volumes: docker volume prune