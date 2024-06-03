~~~ SQL


Monthly sales trend

SELECT
    DATE_FORMAT(STR_TO_DATE(`Order Date`, '%d-%m-%Y'), '%Y-%m-01') AS `Order Month`,
    SUM(`Total Revenue`) AS `Total Revenue`
FROM
    `amazon sales data`
GROUP BY
    DATE_FORMAT(STR_TO_DATE(`Order Date`, '%d-%m-%Y'), '%Y-%m-01')
ORDER BY
    `Order Month`;


Yearly sales trend
SELECT
    DATE_FORMAT(STR_TO_DATE(`Order Date`, '%d-%m-%Y'), '%Y-01-01') AS `Order Year`,
    SUM(`Total Revenue`) AS `Total Revenue`
FROM
    `amazon sales data`
GROUP BY
    DATE_FORMAT(STR_TO_DATE(`Order Date`, '%d-%m-%Y'), '%Y-01-01')
ORDER BY
    `Order Year`;



Peak sales periods (top 5 months)
SELECT
    DATE_FORMAT(STR_TO_DATE(`Order Date`, '%d-%m-%Y'), '%Y-%m-01') AS `Order Month`,
    SUM(`Total Revenue`) AS `Total Revenue`
FROM
    `amazon sales data`
GROUP BY
    DATE_FORMAT(STR_TO_DATE(`Order Date`, '%d-%m-%Y'), '%Y-%m-01')
ORDER BY
    `Total Revenue` DESC
LIMIT 5;



Sales performance by region and country
SELECT
    `Region`,
    `Country`,
    SUM(`Total Revenue`) AS `Total Revenue`,
    SUM(`Total Profit`) AS `Total Profit`
FROM
    `amazon sales data`
GROUP BY
    `Region`, `Country`
ORDER BY
    `Total Revenue` DESC;
