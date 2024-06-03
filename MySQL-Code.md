## Monthly sales trend

SELECT
    DATE_FORMAT(STR_TO_DATE(`Order Date`, '%d-%m-%Y'), '%Y-%m-01') AS `Order Month`,
    SUM(`Total Revenue`) AS `Total Revenue`
FROM
    `amazon sales data`
GROUP BY
    DATE_FORMAT(STR_TO_DATE(`Order Date`, '%d-%m-%Y'), '%Y-%m-01')
ORDER BY
    `Order Month`;
