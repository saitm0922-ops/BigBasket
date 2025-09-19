🛒 BigBasket Data Analysis Project

📌 Project Overview

This project focuses on data analysis of the BigBasket dataset using Python libraries like Pandas, Seaborn, and Matplotlib.
The dataset contains 8208 products across categories such as Fruits & Vegetables, Beauty & Hygiene, Cleaning & Household, Snacks, Beverages, and more.

The main goals were:
✅ Cleaning and preprocessing the dataset
✅ Exploring product categories and prices
✅ Visualizing trends with Seaborn & Matplotlib
✅ Gaining insights into product discounts and pricing strategies

📂 Dataset Information

Rows: 8208

Columns: 9

Key Features:

🏷️ ProductName

🏢 Brand

💰 Price

🏷️ DiscountPrice

🖼️ Image_Url

📦 Quantity

🛍️ Category

🛒 SubCategory

🔗 Absolute_Url

📊 Key Insights

📌 Top 10 Categories by Product Count:

Beauty & Hygiene 🧴

Kitchen, Garden & Pets 🌱

Foodgrains, Oil & Masala 🍚

Cleaning & Household 🧹

Gourmet & World Food 🍫

Snacks & Branded Foods 🍪

Eggs, Meat & Fish 🍗

Bakery, Cakes & Dairy 🥖

Beverages 🥤

Baby Care 👶

📌 Analysis Performed:

Category-wise product distribution

Average product pricing by category

Discounts vs. Price correlation

Boxplots, Histograms & Scatter plots

🛠️ Tech Stack

Python 🐍

Pandas 🐼

Seaborn 🎨

Matplotlib 📈

Google Colab ☁️

📷 Sample Visualizations
🔝 Top 10 Categories
top_categories = data['Category'].value_counts().head(10)
sns.barplot(x=top_categories.index, y=top_categories.values)

💵 Price vs. Discount
data.plot(x='Price', y='DiscountPrice', kind='scatter')

🚀 How to Run

Clone this repo:

git clone https://github.com/your-username/BigBasket-Analysis.git


Install dependencies:

pip install pandas matplotlib seaborn


Run the notebook in Google Colab or locally.

🌟 Conclusion

This project helped uncover valuable insights into product pricing, category distributions, and discount strategies used by BigBasket.

📌 Future improvements could include:

Building an ML model for price prediction

Creating a dashboard for live product analysis

Adding recommendation systems
Author-Raj
