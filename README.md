🍽️ Zomato Data Visualization Project:
A Data Analytics & Visualization Project using Python, Power BI & Excel

📁 Project Overview:
This project analyzes Zomato food delivery and restaurant data to uncover patterns in customer preferences, restaurant ratings, cost distribution, cuisine popularity, and location-wise performance.
The goal is to clean the dataset and build meaningful visualizations and insights that help understand the overall food service ecosystem.

🎯 Project Objectives:
✔ Clean and preprocess Zomato dataset
✔ Analyze restaurant ratings & votes
✔ Identify top cuisines and popular restaurant types
✔ Understand price distribution & cost trends
✔ Visualize location-wise performance
✔ Build business insights for decision-making

🛠️ Tools & Technologies:
Python: Pandas, NumPy, Matplotlib, Seaborn
Jupyter Notebook
Excel / CSV Dataset
Power BI / Tableau (for dashboard)

📂 Dataset Description:
Typical columns in Zomato datasets include:
Column	Description
Restaurant_Name	Name of the restaurant
Location	City or area of the restaurant
Cuisine	Cuisines offered
Rating	Customer rating (0–5)
Votes	Total customer votes
Cost_for_Two	Average cost for two people
Online_Order	Yes / No
Table_Booking	Yes / No
Type	Restaurant type (Casual Dining, Cafe, etc.)

🧹 Data Cleaning Steps:
Removed duplicates
Treated missing values
Standardized inconsistent category values
Cleaned numeric fields (Cost, Ratings, Votes)
Converted columns to correct datatypes
Split cuisines into lists (if required)
Created new calculated fields

📊 Exploratory Data Analysis (EDA):
This project includes:
Top cuisines by popularity
Most rated & most voted restaurants
Cost distribution by restaurant type
Ratings vs votes relationship
Location-wise restaurant performance
Online order availability analysis
Table booking trends
Correlation between price & rating

📈 Visualizations Included:
The notebook & dashboard include visuals like:
Bar chart – Top 10 cuisines
Heatmap – Correlation of numeric attributes
Countplot – Restaurant types
Pie chart – Online order adoption rate
Boxplot – Cost for two distribution
Line chart – Rating trend
Power BI dashboard – Complete restaurant insights

🧠 Key Insights:
Identified most popular cuisines and top-rated restaurants
Found that locations with high votes tend to have better ratings
Observed cost patterns across restaurant types
Discovered strong preference for online orders in urban regions
Highlighted business opportunities for low-coverage cuisine types
Identified places with high restaurant density and competition

📁 Project Structure:
Zomato-Data-Visualization/
│
├── data/
│   └── zomato_data.csv
│
├── notebooks/
│   └── zomato_data_analysis.ipynb
│
├── visuals/
│   ├── top_cuisines.png
│   ├── ratings_distribution.png
│   └── location_view.png
│
├── dashboard/
│   └── Zomato_Dashboard.pbix
│
└── README.md

▶️ How to Run This Project:
1. Clone the repository
git clone https://github.com/your-username/Zomato-Data-Visualization.git
2. Install required dependencies
pip install -r requirements.txt
3. Open the Jupyter Notebook
jupyter notebook
4. Run the analysis
Open and run the file:
zomato_data_analysis.ipynb

🚀 Future Enhancements:
🔹 Integrate sentiment analysis using Zomato reviews
🔹 Build a recommendation model using ML
🔹 Add map-based visualization for restaurant density
🔹 Create a Streamlit interactive dashboard

🤝 Contribution:
Contributions and suggestions are welcome!
Feel free to fork and submit pull requests.
