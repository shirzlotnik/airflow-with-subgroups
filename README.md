# RUN AIRFLOW LOCAL

make sure you have docker running

clone the project

download airflow ->  `pip install apache-airflow`

run in terminal (once) -> `airflow db init`

then, each time you wan to use the airflow, run -> `docker compose up`

the airflow will be at -> http://localhost:8080

username and password are -> `airflow`

when you finish you can run -> `docker compose down`



<br/><br/><br/>
## HOW TO ADD A DAG
<br/>
if you want to add to exisiting one, go to the relevant directory and a python file with you DAG.
<br/>
if you want a new one, create a directory and your DAG to it.

<br/><br/><br/>
## DAG with sub groups with dependencies within and between

![image](https://github.com/user-attachments/assets/edb46577-aebb-40d8-b9a1-77f7c3a2cdbc)

<br/><br/>

![image](https://github.com/user-attachments/assets/0c4b74a1-3407-4ff7-9dc8-2bc9378e862d)

<br/><br/>

![image](https://github.com/user-attachments/assets/4e481d03-3b4b-4f27-befe-54c28f3ca6ac)

