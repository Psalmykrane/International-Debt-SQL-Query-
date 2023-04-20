
# 🏦 The World Bank's International Debt
### Introduction
It's not that we humans only take debts to manage our necessities. A country may also take debt to manage it's economy. For example, infrastructure spending is one costly ingredient required for a country's citizen to lead comfortable lives. The world Bank is the organization that provides debt to countries.

In this project, we are going to analyze international debt data collected by The World Bank. The dataset contains information about the amount of debt in (USD) owed by developing countries across several categories.

#### NOTE :
This is a guided project on DataCamp.




## 📜 Project Objectives

We are going to find answers to questions like:
- What is the total amount of debt that is owed by the countries listed in the dataset?

- Which country owns the maximum amount of debt and what does that amount look like?
- What is the average amount of debt owed by countries across different debt indicators?


This list is not complete — you can extend it with additional questions that come to your mind during the analysis

## 📝 Features
| Column  | Description |
| ------------- | ------------- |
| country_name  | contains name of each country  |
| country_code | a unique three alphabet identifier for each country |
| indicator_name | contains record description |
| indicator_code | a unique code combination for each indicator  |
| debt | amount owed in USD|


## 👨‍💻 Workspace Setup on `Jupyter Notebook`

The first line of code connects us to the international-debt database where the table international_debt is residing. Let's first SELECT all of the columns from the international_debt table. Also, we'll limit the output to the first ten rows to keep the output clean.

```sql
%%sql
postgresql:///international_debt
SELECT *
FROM international_debt
LIMIT 10;
```

## 🛠 Skills
* Data querying
* `SELECT`-ing Data
* Filtering and summarizing Data
* Sorting and Grouping Data
* Writing Readable code
* Debugging
* Error Handling
* PostgreSQL
## 🫂 Contributing

Contributions are always welcome!

Please adhere to this project's `code of conduct`.


## ✍️ Author

- [@Psalmykrane](https://www.github.com/Psalmykrane)

