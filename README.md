# NSE_ETL_Pipeline
**Project Overview**
This project involves the development of a Python-based ETL (Extract, Transform, Load) pipeline to process metadata related to stocks and bonds listed on the NSE (National Stock Exchange). The input dataset includes information from multiple platforms such as Upstox and Dhan. The goal is to standardize, clean, and unify trading symbol data for further use in analytics or trading systems.

**🎯 Purpose**
The pipeline is designed to help analysts, fintech developers, and trading platforms work with clean and consistent market symbol metadata. By automating the data preparation process, this project ensures data quality and facilitates integration into financial applications, dashboards, and APIs.

**Key Features**
Clean and Standardized Output:
Removes duplicates, standardizes names, and ensures symbol consistency across sources (Upstox, Dhan, etc.).

Symbol Matching Across Platforms:
Matches and aligns symbol naming conventions across different brokerage datasets.

Automated Data Transformation:
Handles inconsistent formatting and prepares a final output that is ready for use in applications.

CSV-Based Workflow:
Easy to run with a simple CSV input and generates a clean CSV output.

**Key Data Processed**
Instrument key

Trading symbols

Company names

NSE exchange listings

ISIN and security IDs

Bond and equity classification

**Tools & Technologies**
Python – Core scripting language

Pandas – For data manipulation and cleaning

NumPy – Optional, used for efficient data handling

CSV – Input/output data format

**Conclusion**
This NSE ETL pipeline project demonstrates how data engineering practices can help standardize financial market metadata. By transforming raw CSV data into a clean, ready-to-use format, it supports better integration with financial dashboards, trading systems, and analytical tools. The project is modular, simple to run, and adaptable to other financial instruments or data sources.
