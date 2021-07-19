<p align="center">
  <a href="" rel="noopener">
 <img height=150px src="https://raw.githubusercontent.com/databricks/koalas/master/icons/koalas-logo.png" alt="Project logo"></a>
</p>

<h3 align="center"> Koalas is an open-source project that provides a drop-in replacement for pandas. commonly used by data scientists to clean large volumes of data.</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

## 📝 Table of Contents

- [About](#about)
- [Architeture](#architeture)
- [Usage](#usage)
- [Authors](#authors)

## 🧐 About <a name = "about"></a>

In this project we will explore a little of how Koalas can help us in data processing, using various techniques from converting json file types to parquet, to gain performance and storage reduction in data storage, using SQL for application of rules of business, using UDF functions, and plotting graphs using native Koalas libraries.

## 🔧 Architeture Koalas <a name = "architeture"></a>

![image](https://images.squarespace-cdn.com/content/v1/5bce4071ab1a620db382773e/1594040415825-EZTBJS5O882UMWWBV6PT/Koalas+API.jpg?format=1000w)

### Prerequisites

```
Spark: 3.1.1 https://spark.apache.org/downloads.html

https://docs.databricks.com/languages/koalas.html#requirements
```

## 🎈 Usage <a name="usage"></a>

To use the technical laboratory used, I made available a jupyter notebook in which we used several features that the databricks.koalas library, for each cell of the notebook you can observe the techniques used, reading data in json, displaying dataframe using the head method, writing of data in parquet format, reading of data in parquet format, field typing conversion, DataFrame schema identification, selection of specific columns using the loc method, join using lsuffix and rsuffix, we can also use SQL using the native koalas library , reusing parameters created in python without the need for F string, UDF functions and how to plot graphs in koalas.

## ✍️ Authors <a name = "authors"></a>

- [@carlosbpy](https://github.com/carlosbpy) - Idea & Initial work