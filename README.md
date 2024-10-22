# Secure-Sensitive Data Processing Platform

The project aims to create a secure data processing platform for sensitive data while incorporating critical security features. The system is built with Flask-based APIs for parameterized data queries and Docker containers for quick deployment. Databricks manages scalable data processing and storage in Delta format.

Goal: Develop a Dockerized application that accepts a date range, retrieves hourly data, and stores it in Databricks and Azure Storage. Unity Catalog is used to maintain data provenance and manage Personally Identifiable Information (PII) flags, which improves data governance and security.

Key Security Features:

Advanced cryptography modules are used to encrypt sensitive data such as email addresses and phone numbers, ensuring confidentiality and integrity.

Unity Catalog is used for data lineage and governance, allowing secure exchange within and beyond the company. Ongoing upgrades will include PII flagging for automated encryption compliance. This platform prioritizes data governance, security, and confidentiality, particularly for sensitive data.
