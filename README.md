# SQL for Data Engineering using PostgreSQL
 
- This project focuses on creating databases, tables and connect relationally and finally dump huge e-commerce data into the database tables.
- All these tasks were accomplished using python.
- PostgreSQL is used as the Relational Database Management System, as it is an open-source system and highly demanded in use case.

- Used *SQLAlchemy* for dumping or inserting the data into the database tables. As the manual insertion process through looping takes a lot of time and computationally not recommendable
  while dealing huge data.
  
  **SQLAlchemy** - a Python library that provides a high-level Object-Relational Mapping (ORM) system for interacting with databases, along with a flexible SQL Expression Language for
  executing raw SQL queries.
- *SQLAlchemy* helps in pushing the whole data into the database tables at one go.

**libraries used in python**
```python
import pandas as pd
import psycopg2 as psy
from sqlalchemy import create_engine
```

- Refer `instamart_postgresql@jupy.ipynb` for code
- Source of Data Set is from Kaggle
  
  Download it from: [Data Set](https://drive.google.com/drive/folders/1pjmEQOxse7Q3kldm7YPBUANS4Nlo7rCc?usp=drive_link)

  ### Once the data loads, Start Analysing...
