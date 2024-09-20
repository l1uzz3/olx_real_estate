# OLX real estate project
### This project is an inspiration from @sspaeti's project (https://github.com/ssp-data/practical-data-engineering/) adapted to Romanian real estate.
#### This is a data application that will collect real-estates coupled with Google maps way calculation but potential other macro or microeconomics like taxes, the population of city, schools, public transportation. Enriched with machine learning correlations to know factors that influence the price the most.
##### **PREREQUISITES:**

- **IDE:** ==DataSpell== – Main development environment for Python, integrating data science features for ease of coding and testing.

- **CI/CD:** ==GitHub / Git Bash== – Version control with GitHub for collaboration and Git Bash for command-line Git operations.

- **Containerization**: ==Docker== – Ensures consistency in development by containerizing all dependencies.

- **Storage**: ==MinIO== – Provides object storage to manage raw and processed data **(data lake)**.

- **Data processing/stream:** ==Apache Spark== – Processes and analyzes large datasets.

- **Orchestration:** ==Airflow== – Manages scheduling and workflow of your data pipelines.

 - **Deployment:** ==Kubernetes== – Ensures scalability for your containerized applications (optional but useful for large projects).
