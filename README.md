# Stationery Sales Analytics (Excel Dashboards)

A multi-dashboard Excel project analysing stationery sales by brand, product, zone, state and sales channel.

## Dataset
- 1,755 daily sales records, 23 fields
- 6 brands (Apsara, Camel, Classmate, Doms, Faber Castle, Natraj), 7 products, 4 zones, 9 states
- Fields include quantity, unit price, net sales, net cost, customers, business type (B2B/B2C), sales channel and payment mode
- Synthetic sample data created for practice

## Tools
Excel: Pivot Tables, INDEX-MATCH, VLOOKUP, MAX, Slicers, Timeline, charts

## What I built
- 23 pivot tables and 50+ charts
- 7 dashboards: 1 overall and 1 per brand
- Slicers (product, business type, weekday/weekend) and a date timeline
- Formula that finds each brand's top product with MAX + INDEX-MATCH

## Key findings
<!-- Fill in after the data fixes: e.g. top product per brand, best state, channel share -->
- 
- 
- 

## Dashboard
![Overall dashboard](images/overall_dashboard.png)

## Data notes
- `MARGIN` is profit per unit; total profit = NET SALES − NET COST.
- `CUSTOMERS` is a per-record count, so summing it gives customer visits, not unique customers.

## Files
```
data/       main data
workbook/   stationery_sales_dashboard.xlsx
images/     dashboard screenshots
```

## Author
Ayush Kumar · [LinkedIn](https://www.linkedin.com/in/ayush-kumar-214742443) · ayushkum5591@gmail.com
