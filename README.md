## **Amazon Sales Data Analysis: Insights into Product Ratings, Pricing, and Customer Reviews**

### **Project Objective:**
To analyze the Amazon Sales Dataset to uncover insights about product ratings, pricing, discounts, and customer reviews across different categories. The analysis will help identify trends, popular products, and factors influencing customer satisfaction.

### **Dataset Description:**

- Taken from kaggle.
- The dataset used in this project contains Amazon product sales data, including **product ratings, pricing, customer reviews, and discount information**. 
- This dataset helps in understanding the relationship between pricing, customer feedback, and overall product performance.

### **Key Objectives**
- **Understand customer sentiments** from product reviews.
- **Analyze the impact of pricing and discounts** on ratings.
- **Identify commonly used keywords** in reviews to determine product expectations.
- **Detect trends** in frequently purchased product categories.

### **Key Insights**
- **Most products have high ratings (3.5 - 5 stars).**
- **98.2% of reviews are positive**, with keywords like *"good," "useful," and "durable."*
- **No strong correlation between price and rating** → Customers prioritize **quality over discounts**.
- **Charging accessories (USB cables, power banks) are highly purchased**.

### **Repository Structure**
📂 Amazon Sales Data Analysis - Insights into Product Ratings, Pricing, and Customer Reviews

├── 📁 images/     # Contains saved visualizations (static PNGs for GitHub)

├── 📁 src/ 

        ├── amazon.csv # Dataset taken from kaggle

├── 📄 eda.ipynb     # Exploratory Data Analysis (EDA) notebook

├── 📄 README.md     # Project documentation

├── 📄 requirements.txt     # Dependencies for running the project

### **Handling Interactive Plots on GitHub**
GitHub does not support interactive visualizations (e.g., Plotly, seaborn interactive charts). 
To ensure accessibility, we have **saved visualizations as both PNG and HTML files**:

- **PNG files** → Static images for easy viewing.
- **HTML files** → Interactive charts can be opened in a browser.

### **Visualizations**
- **Interactive Plots**: Created using Plotly to explore trends and patterns.
- **Saving Plots**: Due to GitHub's limitations in supporting interactive plots, visualizations are saved as PNG and HTML files. To view the interactive plots, download the HTML files and open them in a web browser.

### **Skills Demonstrated**
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization using Plotly
- Insight Generation and Reporting

### **How to Run the Analysis**
1. Clone the repository

2. Install dependencies:
        
```bash
pip install -r requirements.txt
```

3. Run `eda.ipynb` for detailed analysis and visualizations.

4. Download HTML files to view interactive plots.

### **Conclusions & Recommendations**

- Focus on product quality and warranty over just pricing.
- Charging accessories are in high demand, making them a good investment.
- Enhancing durability and usability can lead to higher customer satisfaction
- Develop a Dashboard to show kpis.