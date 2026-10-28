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
Figures cover all 1,755 records with no filters applied. Profit = Net Sales − Net Cost.

- **Overall:** total net sales 1,394,575 and net cost 446,118, a profit of 948,457 (**68% margin**) on 94,645 units sold.
- **Notebook is the star product:** 35.4% of all sales from only 223 of 1,755 records, with the highest margin (82.5%). It is the top seller for 5 of 6 brands; Doms is the exception (Geometry Box).
- **Geometry Box is second** (24.4% of sales). Pencil has the lowest margin (40%), while Pen, Scale, Eraser and Geometry Box all earn 60%.
- **Price, not volume, drives revenue:** units sold are similar for every product (about 12,300 to 14,900 each). Notebook sold the fewest units but earned the most, while Eraser, Pencil and Scale together are under 15% of sales.
- **Brands are closely matched:** Natraj leads (18.3% of sales), then Classmate (17.7%) and Camel (17.1%); Apsara and Faber Castle trail at 15.2% each. Camel has the best margin (70%).
- **Punjab is the top state** with 19.9% of sales, well ahead of Maharashtra (12.7%) and Sikkim (12.2%). West Bengal is lowest (8.1%).
- **Channels are balanced:** Amazon 26.7%, Flipkart 26.2%, Store 24.4%, Website 22.6%. Amazon and Flipkart together bring in 52.9% of sales.
- **B2B and B2C are split evenly** (50.8% vs 49.2%), and so are male and female customers (50.3% vs 49.7%).
- **UPI is the most-used payment mode** at 50.4% of sales, followed by Cash (26.0%) and Credit (23.6%).

## Dashboard
<img width="1337" height="835" alt="image" src="https://github.com/user-attachments/assets/5fde91bd-d633-46bc-9a0a-26523d41c3b9" />


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
