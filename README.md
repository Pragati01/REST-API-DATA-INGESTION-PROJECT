#  REST API to Neon PostgreSQL Ingestion (via Google Colab)

This project demonstrates how to fetch data from a public REST API, transform it using Python in Google Colab, and load it into a serverless PostgreSQL database hosted on [Neon](https://neon.tech). This data is queried using [DBeaver](https://dbeaver.io/). It uses an English-readable dataset (`https://jsonplaceholder.typicode.com/users`) and includes an automatic `load_date` column for tracking.

---

##  Features

- Ingest data from a live REST API
- Flatten nested JSON using `pandas.json_normalize()`
- Add a `load_date` column for ingestion tracking
- Load data into Neon (serverless PostgreSQL)
- Access and query the data using DBeaver or Colab
- No local installation required — works entirely in the cloud

---

##  Technologies Used

- [Google Colab](https://colab.research.google.com/)
- [Neon](https://neon.tech/)
- [PostgreSQL](https://www.postgresql.org/)
- [DBeaver](https://dbeaver.io/)
- Python libraries:
  - `requests`
  - `pandas`
  - `sqlalchemy`
  - `psycopg2-binary`

---

## 📁 Files

| File              | Description                                |Link
|-------------------|--------------------------------------------|-------------------------------------------------------------------------------------------------
| `notebook.ipynb`  | Google Colab notebook with the ETL script  | https://colab.research.google.com/drive/1B2LmRuC1FT701U5_RYrrSxYaAEeo4AFI#scrollTo=aMimhwUREvdF

---


