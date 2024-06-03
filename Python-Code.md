~~~ Python

pythonCopy code
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

# Load the cleaned dataset from Excel
df = pd.read_excel('cleaned_sales_data.xlsx')

# Summary statistics
print(df.describe())

# Visualize sales distribution
sns.histplot(df['Units Sold'], kde=True)
plt.title('Distribution of Units Sold')
plt.xlabel('Units Sold')
plt.ylabel('Frequency')
plt.show()

# Time series analysis
df['Order Date'] = pd.to_datetime(df['Order Date'])
monthly_sales = df.groupby(df['Order Date'].dt.to_period('M')).agg({'Total Revenue': 'sum'}).reset_index()
monthly_sales['Order Date'] = monthly_sales['Order Date'].dt.to_timestamp()

plt.figure(figsize=(12, 6))
sns.lineplot(x='Order Date', y='Total Revenue', data=monthly_sales)
plt.title('Monthly Sales Trend')
plt.xlabel('Month')
plt.ylabel('Total Revenue')
plt.show()

