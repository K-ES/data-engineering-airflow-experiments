# Airflow Learning Log 📝


26.11.2025
---

- Configured PyCharm to use the WSL Python interpreter from ~/airflow/venv/bin/python.
- Airflow imports stopped showing errors in the editor.
- Launched webserver and scheduler inside WSL.
- Checked the Airflow SQLite metadata database and inspected table schemas.
- Confirmed that SequentialExecutor is normal when using SQLite.
- Learned that Airflow reads DAGs only from ~/airflow/dags.
- Prepared the solution to expose the project to Airflow using a symbolic link.

- Настроил PyCharm на использование WSL-интерпретатора Python из ~/airflow/venv/bin/python.
- Исчезли ошибки импорта Airflow в редакторе.
- Запустил webserver и scheduler внутри WSL.
- Проверил SQLite-базу метаданных Airflow и изучил схемы таблиц.
- Убедился, что SequentialExecutor — это норма при работе с SQLite.
- Разобрался, что Airflow читает DAG-и только из ~/airflow/dags.
- Подготовил решение — создать симлинк, чтобы Airflow видел проект из рабочей директории.

14.09.2025
---

- Installed **Python 3.11** on WSL (Ubuntu).  
- Created a virtual environment `venv` in `~/airflow`.  
- Installed **Apache Airflow 2.9.3** with pip.  
- Initialized the Airflow database (`airflow db init`).  
- Created a new admin user (`admin / admin`).  
- Successfully launched **webserver** and **scheduler**.  
- Logged into the Airflow UI at [http://localhost:8080](http://localhost:8080).  

✅ Airflow is running locally on WSL.  
---

- Установил **Python 3.11** в WSL (Ubuntu).  
- Создал виртуальное окружение `venv` в `~/airflow`.  
- Установил **Apache Airflow 2.9.3** через pip.  
- Инициализировал базу данных Airflow (`airflow db init`).  
- Создал нового пользователя admin (`admin / admin`).  
- Успешно запустил **webserver** и **scheduler**.  
- Зашёл в интерфейс Airflow по адресу [http://localhost:8080](http://localhost:8080).  

✅ Airflow работает локально в WSL.  
---
