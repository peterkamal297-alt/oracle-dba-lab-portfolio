# 🗄️ 02 — Oracle Database 19c Installation

## 📌 Overview
This module documents the manual, end-to-end deployment of Oracle Database 19c Enterprise Edition software binaries and the creation of a production-ready Container Database (CDB) architecture.

## 🛠️ Key Technical Tasks & Implementation
* **Prerequisites Validation:** Executed pre-installation checks, package dependencies resolution, and kernel adjustments.
* **Software Binaries Setup:** Configured Oracle Inventory, extracted enterprise software binaries under `/u01/app/oracle/product/19.3.0/dbhome_1`.
* **Listener & Network Configuration:** Configured `listener.ora` and `tnsnames.ora` for seamless client and server communication.
* **Database Creation:** Deployed a Container Database (CDB) with a Pluggable Database (PDB) using Oracle Database Configuration Assistant (DBCA) and silent scripts.

## 📁 Files & Documentation
* [Oracle 19c Installation Guide (PDF)](./oracle-installation.pdf)
