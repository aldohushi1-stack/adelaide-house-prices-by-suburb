# Adelaide house prices by suburb (2026)

Median house prices, sales counts, rents and gross yields for all 438 Adelaide metropolitan suburbs, built from South Australian Government open data. One row per suburb, one file.

**Live data and a page for every suburb: [aldo.today](https://aldo.today/)**

## Download

The current file is always at **[aldo.today/adelaide.csv](https://aldo.today/adelaide.csv)** (about 60 KB, UTF-8, 438 rows). It is regenerated when the Valuer-General publishes a new quarter.

## What is in it

| Column | Meaning |
|---|---|
| suburb, postcode, council | Suburb name, postcode and local council |
| median_house_price_12m | Sales-weighted median of the last four quarterly house medians (12 months to June 2026) |
| house_sales_12m | House sales behind that median |
| change_1y_pct, change_5y_pct | Change on the same 12 months one and five years earlier |
| typical_block_m2, land_per_m2 | Typical block size, and median price divided by it |
| price_rank | Rank among suburbs with 20 or more sales |
| url | The suburb's page on aldo.today |
| house_rent_week, house_bonds, rent_level | Median weekly house rent from new bonds lodged, the bond count, and whether it is the suburb's own figure or its postcode's |
| gross_yield_pct | Annual rent over median price, where both are the suburb's own |
| house_rent_change_1y_pct, house_rent_change_5y_pct | Change in median house rent |
| unit_rent_week, unit_bonds, unit_rent_level | The same for flats and units |

## Read this before you chart it

Small suburbs swing. A suburb with fewer than 40 house sales in a year can move 20% or more on which houses happened to sell, not on what every house is worth. Use house_sales_12m to filter, or see [why small suburbs jump](https://aldo.today/about-the-data).

## Sources and licence

Sales medians: SA Valuer-General, quarterly median house prices by suburb, via [Data.SA](https://data.sa.gov.au/) (CC BY 4.0).
Rents: Private Rent Report, SA Housing Trust, from Consumer and Business Services bond data, via Data.SA (CC BY 4.0).
Method: [how the numbers are made](https://aldo.today/about-the-data).

This compilation is released under CC BY 4.0. If you use it, please credit: **"SA Valuer-General via Data.SA, compiled by aldo.today"** and link to https://aldo.today/.

Not a valuation and not financial advice. A suburb median is a guide to a suburb, not a price for a house.
