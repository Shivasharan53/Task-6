STRFTIME('%Y', "Order Date"): Extracts the year component from the order date.

STRFTIME('%m', "Order Date"): Extracts the month component from the order date.

SUM(Sales): Computes the total revenue for each month.

COUNT(DISTINCT "Order ID"): Retrieves the count of distinct orders in that period.

GROUP BY year, month: Aggregates the results by year and month to summarize data at a monthly granularity.

ORDER BY year, month: Sorts the summarized results in time sequence for readability.
