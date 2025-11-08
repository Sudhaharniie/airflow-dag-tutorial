# airflow-dag-tutorial
Basic steps to create an Airflow DAG with screenshots

# Airflow DAG Tutorial

This repository contains a step-by-step guide to create a basic **ETL DAG** in **Apache Airflow** along with screenshots and a Word file documenting the steps. This project is designed as a beginner-friendly tutorial for learning Airflow workflows.

---
## Project Structure
AirflowTutorial/
│   airflow_steps.docx          # Word file with step-by-step guide and screenshots
│
├───dags
│       etl_dag.py              # Example ETL DAG Python file
│
└───screenshots
dag_graph.png           # DAG Graph View screenshot
task_log.png            # Task Instance logs screenshot

---

## Description

- **Word file (`airflow_steps.docx`)**: Contains detailed instructions on:
  - Installing and setting up Apache Airflow
  - Creating a DAG
  - Taking screenshots of DAG execution and Graph View  

- **DAG Python file (`dags/etl_dag.py`)**: A simple ETL DAG with three tasks:
  1. `extract` – simulates data extraction  
  2. `transform` – simulates data transformation  
  3. `load` – simulates data loading  

- **Screenshots (`screenshots/`)**: Visual proof of DAG execution in Airflow UI, showing Graph View and Task Instance logs.

---

## How to Use

1. **Install Apache Airflow** (follow official instructions):  
   [https://airflow.apache.org/docs/apache-airflow/stable/installation/index.html](https://airflow.apache.org/docs/apache-airflow/stable/installation/index.html)

2. **Place the DAG file** in your Airflow DAGs folder:

```bash
# Example:
cp dags/etl_dag.py ~/airflow/dags/



Start Airflow Webserver and Scheduler:


airflow webserver --port 8080
airflow scheduler



Open Airflow UI in your browser:


http://localhost:8080



Activate and trigger the DAG etl_dag.


View Graph View in the UI to see the workflow:


extract → transform → load



Check task logs for each step to verify execution.



Screenshots


DAG Graph View: screenshots/dag_graph.png


Task Instance Logs: screenshots/task_log.png


(Place screenshots here for visual reference.)

Purpose


Demonstrates a basic ETL workflow in Airflow.


Provides a beginner-friendly guide with code, Word documentation, and screenshots.


Can be used as a reference for building more complex DAGs.



Author
Sudhaharniie


GitHub: https://github.com/Sudhaharniie



License
This project is for educational purposes. You can copy and modify for learning.

---

✅ This is **everything to include in `README.md`** for your Airflow DAG tutorial project:  
- Clear **project structure**  
- **Step-by-step instructions** to run the DAG  
- Screenshots section  
- Author info  
- Purpose and license  

---

If you want, I can also **enhance this README** by **embedding the DAG screenshot directly in the README**, so the Graph View appears on GitHub without opening Airflow — it looks more professional.  

Do you want me to do that?




