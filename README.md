# Sales forecasting for 4 weeks


The dataset underwent preprocessing to transform its structure for clearer insights. Initially, the 'InvoiceDate' column was converted to a datetime format. Subsequently, a new column named 'TotalPrice' was introduced, representing the product of 'Quantity' and 'UnitPrice' to denote the total price for each transaction. The data was then grouped by 'InvoiceDate', and the sum of 'Quantity' and 'TotalPrice' was calculated for each date. The resulting DataFrame now comprises entries for distinct dates, accompanied by corresponding aggregated values for and 'TotalPrice'.
