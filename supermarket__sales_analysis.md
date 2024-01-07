### -- 1. Retrieve the total gross income for each branch and product line.

### SELECT Branch, ProductLine, SUM(`gross income`) AS TotalGrossIncome FROM YourTableName GROUP BY Branch, ProductLine;

### --2. Find the average rating for each product line.

### SELECT ProductLine, AVG(Rating) AS AverageRating FROM YourTableName GROUP BY ProductLine;

### --3. Identify the top 5 customers with the highest total spending.
### SELECT `Customer type`, Gender, SUM(Total) AS TotalSpending FROM YourTableName GROUP BY `Customer type`, Gender ORDER BY TotalSpending DESC LIMIT 5;

### --4. Calculate the monthly average gross margin percentage for each city.
### SELECT City, AVG(`gross margin percentage`) AS AvgGrossMarginPercentage FROM YourTableName GROUP BY City, MONTH(Date);










