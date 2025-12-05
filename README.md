# Adventure Works 2022 - Sales Dashboard (Power BI)

This report explores sales data from the Adventure Works 2022 dataset.  
The idea was to go from raw tables to a clean model, build the right measures, and then highlight useful insights visually.

---

## What the report covers
- Year-to-year revenue changes
- Regional/Territory performance
- Product category behavior (units vs. revenue)
- Shipping method patterns
- KPIs and slicers to explore the data easily

---

## Workflow & Tools
- SQL Server → pulled the tables I needed
- Power Query → cleaned and reshaped everything
- Data Model → star schema + custom Date table
- DAX → measures for revenue, YoY, growth %, etc.
- Power BI → visuals and interactions

---

## A few notes  
Creating the custom Date table made the time comparisons (YoY, YTD, etc.) much more reliable.  
A lot of the interesting insights only showed clearly after structuring the model properly.

---

## Dashboard Preview

![Page_1](screenshots/Sales-Performance-Overview)
![Page 2](screenshots/Product&Customer-Deep-Dive)
![Page 3](screenshots/DataModeling)


---

## Dataset
Adventure Works 2022 (Microsoft sample)

---

## Contact
If you have any thoughts, ideas, or feedback, feel free to reach out.
