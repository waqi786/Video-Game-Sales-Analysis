# 📌 Video Game Sales Analysis  

A comprehensive exploratory data analysis (EDA) of video game sales data, examining trends across different platforms, publishers, and regions.  

## 📂 Project Overview  
This project focuses on analyzing **video game sales data** using **Python** and key data science libraries. The dataset includes information on game titles, platforms, release years, sales across different regions, and publishers. Through data cleaning, visualization, and insights extraction, this analysis provides valuable perspectives on gaming industry trends.  

### 🔍 Objectives:  
- Clean and preprocess the dataset by handling missing values and duplicates.  
- Perform exploratory data analysis (EDA) to uncover key trends.  
- Visualize sales distributions across different platforms, genres, and regions.  
- Identify the top-selling games and publishers.  
- Analyze yearly sales trends and their impact on the gaming industry.  

## 📊 Dataset Information  
- **Source:** [Kaggle - Video Game Sales Dataset](https://www.kaggle.com/code/waqi786/video-game-sales-analysis)  
- **File Used:** `vgsales.csv`  
- **Columns Included:**  
  - `Rank` – Global ranking of the game based on sales.  
  - `Name` – Title of the game.  
  - `Platform` – Console/platform on which the game was released.  
  - `Year` – Year of release.  
  - `Genre` – Game category (e.g., Action, Sports, Racing, etc.).  
  - `Publisher` – Name of the publishing company.  
  - `NA_Sales`, `EU_Sales`, `JP_Sales`, `Other_Sales` – Sales figures in different regions (in millions).  
  - `Global_Sales` – Total worldwide sales (in millions).  

## ⚙ Installation & Setup  
To run this project on your local machine, follow these steps:  

### 1️⃣ Clone the Repository  
git clone https://github.com/yourusername/Video-Game-Sales-Analysis.git cd Video-Game-Sales-Analysis


### 2️⃣ Install Required Libraries  
Ensure you have Python installed. Then, install the necessary dependencies:  

pip install pandas numpy matplotlib seaborn

### 3️⃣ Run the Jupyter Notebook  

jupyter notebook

Open the `Video_Game_Sales_Analysis.ipynb` file and execute the cells sequentially.  

## 📌 Exploratory Data Analysis (EDA)  
### 🔹 1. Data Cleaning & Preprocessing  
- Handled missing values in the `Year` and `Publisher` columns.  
- Removed duplicate entries to ensure data consistency.  

### 🔹 2. Descriptive Statistics & Summary  
- Used `.info()`, `.describe()`, and `.isnull().sum()` to get dataset insights.  
- Identified the most common game genres and platforms.  

### 🔹 3. Correlation Analysis  
- Generated a **correlation heatmap** to understand relationships between numeric features.  
- Explored sales patterns across different platforms and regions.  

### 🔹 4. Sales Trends & Insights  
✅ **Yearly Sales Trend:** 📈 Analyzed total sales over time to understand market growth.  
✅ **Most Popular Platforms & Publishers:** 🎮 Identified the top platforms and publishers driving the gaming industry.  
✅ **Regional Sales Distribution:** 🌍 Examined sales performance across **North America, Europe, Japan, and Other Regions**.  
✅ **Genre Popularity:** 🕹️ Visualized the most common game genres based on sales volume.  

## 📈 Key Visualizations & Findings  
- **Global Sales Over Time:** Line graph to visualize yearly trends.  
- **Top 10 Gaming Platforms:** Bar chart showcasing the most successful gaming consoles.  
- **Publisher Performance:** Analyzed game distribution by publisher.  
- **Regional Sales Distribution:** Pie chart and bar plot representing market share.  

🔹 The dataset reveals that **Action and Sports games** are the most dominant genres.  
🔹 **Nintendo, Sony, and Microsoft** have been key players in the gaming industry.  
🔹 Sales performance **varies significantly** across different geographic regions.  

## 🏆 Next Steps & Future Enhancements  
- Implement **Machine Learning models** for **predicting video game sales**.  
- Explore **sentiment analysis** on game reviews to correlate with sales trends.  
- Use **interactive dashboards (Plotly, Dash, or Tableau)** for better data visualization.  

## 🛠 Technologies Used  
- **Programming Language:** Python 🐍  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Visualization Tools:** Matplotlib, Seaborn  

## 📜 License  
This project is open-source and available under the **MIT License**.  

## 🤝 Contributing  
Contributions are welcome! Feel free to fork this repository, improve the code, and submit a pull request.  

## 📬 Contact  
📧 Email: dsali20838@gmail.com 

🌐 GitHub: [YourUsername](https://github.com/waqi786)  

🔗 Kaggle: [Waqar Ali](https://www.kaggle.com/waqi786)  
