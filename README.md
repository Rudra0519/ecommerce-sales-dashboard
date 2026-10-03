# E Commerce Sales Dashboard

An individual Power BI project by Rudra Patel. Started January 2026; the dashboard is completed.

## Dashboard scope

The report uses Orders and Details tables and provides sales amount, profit and quantity summaries, monthly profit trends, sub-category comparisons, state and customer views, and category/payment-method quantity breakdowns. Quarter and state slicers support exploration.

Open `ecommerce-sales.pbix` in Power BI Desktop to inspect the saved dashboard. Original source CSVs were not included with the supplied file, so refresh paths must be checked and the original sources supplied before reproducing a refresh.

## Calculation review

The report structure was inspected during portfolio preparation, but the embedded model was not recalculated. Displayed totals use implicit aggregations. A card references `Sum(Details.AOV)`; treat this as an unresolved metric definition rather than a verified average order value. Validate total sales divided by distinct order count at the intended grain before drawing an AOV conclusion.

## Next improvements

Document the source and units; validate relationships and totals; define explicit measures; add readable screenshots and three findings supported by source-data checks. This practice dashboard does not establish real business impact.
