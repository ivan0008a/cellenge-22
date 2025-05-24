# Home Sales – Spark SQL & Parquet Analysis

This repository contains the **Home\_Sales** big-data assignment completed in Google Colab.  The notebook walks through loading a public real-estate CSV, running analytical Spark SQL queries, caching, writing Parquet with partitioning, and comparing runtimes.




 Quick Start

1. **Open** `Home_Sales.ipynb` in Google Colab.
2. **Run All** (⌘/Ctrl + F9) or execute step-by-step:

   * Install PySpark.
   * Load the CSV from the public S3 bucket.
   * Create a temp view and answer four analytical questions via Spark SQL.
   * Cache the table, time the query again.
   * Write the data out as Parquet partitioned by `date_built` and compare runtimes.
   * Un-cache table and verify.
3. Review printed runtimes and query results in the output cells.
4. (Optional) Download the generated Parquet folder for local inspection.

---

## 📝  Assignment Tasks Covered

* **DataFrame Creation** from a public S3 CSV.
* **Temporary View** creation for SparkSQL.
* **Analytical Queries** answering:

  1. Average price of 4-bed homes sold each year.
  2. Average price of 3-bed/3-bath homes by year built.
  3. Same as (2) plus floors = 2 and ≥ 2 000 sq ft.
  4. Average price per `view` rating where average ≥ \$350 000.
* **Performance Comparison** (uncached vs cached vs Parquet partitioned).
* **Caching / Un-caching** data in Spark.

---

