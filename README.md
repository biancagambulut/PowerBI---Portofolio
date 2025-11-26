🇬🇧 Population Aged 0–3 Across European Countries
📌 Project Overview

This Power BI dashboard analyzes the population aged 0–3 across European countries.
The goal is to identify demographic patterns, gender distribution, and top/extreme countries in terms of early childhood population.

This project demonstrates skills in:

  -Data transformation and modeling

  -Dimensional modeling

  -DAX and analytical measures

  -Designing professional dashboards

  -Extracting business insights

  -Using Eurostat open data

📊 Data Source

  -Eurostat official open datasets

  -Time period: latest available years

  -Countries included: 27 European countries

The data was cleaned, appended and prepared in Power BI, using:

  -Dim Year

  -Dim Country

  -Fact Population

🧩 Data Model

✔️ Relationships were created using:

Year → Fact Population (1:M)

Country Code → Country Name (1:M)

✔️ Data transformation steps:

Remove duplicates

Append multiple files

Apply filters for ages 0–3

Create separate dimension tables

🔢 KPIs and DAX Measures

Key metrics included:

Total children aged 0–3

Total girls aged 0–3

Total boys aged 0–3

% gender distribution

Top/Min population countries

Average children per country

Example measures:

Total Children = SUM(FactPopulation[Population])
Girls = SUM(FactPopulation[Girls])
Boys = SUM(FactPopulation[Boys])
%Girls = DIVIDE([Girls], [Total Children])
%Boys = DIVIDE([Boys], [Total Children])

📸 Dashboard Screenshots
Page 1 – Overview

Page 2 – Country-level Analysis

Page 3 – Gender and Trend Analysis

Page 4 – Insights and Conclusions

🧠 Insights & Analysis

Turkey has the highest 0–3 population (≈20% of Europe).

Liechtenstein has the smallest 0–3 population, almost zero.

Gender distribution is balanced overall, 51% boys, 49% girls.

Western European countries dominate the top demographic ranking.

Top 5 countries represent more than 50% of the total European population.

🏁 Conclusion

The dashboard offers a clear demographic overview and reveals major population patterns and distribution across Europe. This analysis is useful for:

demographic studies

urban planning

education and healthcare demand

social policy
