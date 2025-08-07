# StoryTelling_HousingAnaysis
# 🏡 Storytelling Assignment: Explore a Housing Prices Dataset Using Pandas

This project uncovers insights from a housing prices dataset through data storytelling. Using Pandas, Matplotlib, and Seaborn, we explore trends in property prices, area sizes, and bedroom counts to narrate the dynamics of the housing market.


---

## 📁 Project Structure

- `Housing.csv`: Dataset containing property listings
- `Zahab_HousingAnalysis.ipynb`: Google Colab notebook with data cleaning, exploration, and storytelling
- `README.md`: Project overview and narrative summary
- Colab Link :[Housing_Analysis](https://colab.research.google.com/drive/13FVWJKbVCUIW_XrNevWFh_bHzSKGAEwM?usp=sharing)

---

## 🎯 Objective

The goal of this assignment is to:
- Use Pandas for data manipulation and analysis
- Apply statistical techniques to summarize key features
- Create compelling visualizations to support insights
- Tell a meaningful story about housing market trends

---

## ⚙️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/storytelling-housing-prices.git
   cd storytelling-housing-prices

---


2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

3. Run the notebook:
   ```bash
   jupyter notebook housing_analysis.ipynb
   ```

---

## 📊 Data Overview

The dataset contains 545 property listings with the following key features:
- `price`: Property price in USD
- `area`: Property size in square feet
- `bedrooms`: Number of bedrooms
- Additional features include bathrooms, stories, parking, and amenities

---

## 🔍 Statistical Summary

### Price
- **Average**: $4.77 million  
- **Median**: $4.34 million  
- **Range**: $1.75M – $13.3M  
- **Standard Deviation**: $1.87 million  
- **Skewness**: 1.21 (right-skewed)  
- **Kurtosis**: 1.96 (presence of outliers)

### Area
- **Average**: 5,150 sq ft  
- **Median**: 4,600 sq ft  
- **Range**: 1,650 – 16,200 sq ft  
- **Standard Deviation**: 2,170 sq ft  
- **Skewness**: 1.32  
- **Kurtosis**: 2.75

---

## 📈 Visualizations

- **Box Plots**: Show distribution and outliers for price and area  
- **Histograms**: Reveal frequency and skewness of price and area  
- **Scatter Plot**: Price vs Area, color-coded by bedroom count  
- **Bar Chart**: Average price per bedroom category
- **Correlation Heatmap** : Categorical variables were encoded using pd.get_dummies() to compute correlations.
-**Pair Plot Analysis**: Used to explore relationships between numerical variables and how they vary across categories.



- 

  


- 


All plots are created using Seaborn and Matplotlib for clear and informative visuals.

---

## 🧠 Key Insights

### Housing Price Overview  
Prices vary widely, with a few luxury listings significantly raising the average. The distribution is skewed toward lower-priced homes, but outliers are present.

### Price Distribution and Outliers  
High kurtosis and skewness indicate a market with both affordable and premium properties. Outliers suggest opportunities for high-end investment.

### Property Area Analysis  
Most homes are moderately sized, but the presence of very large properties adds diversity to the market.

### Market Diversity  
The data reflects a dynamic housing market with no single dominant category. Buyers and sellers should consider the full range of options when making decisions.

##Further  Key Takeaways
- Price and area show wide variability and positive skew.
- Furnishing status significantly influences pricing.
- Visualizations like histograms, box plots, and violin plots reveal deep insights.
- Pair plots and heatmaps help uncover relationships between features.




---

## 📌 Future Work

- Add location-based analysis (e.g., preferred areas)
- Explore correlation between amenities and pricing
- Build an interactive dashboard using Streamlit

---

##  Acknowledgments

Thanks to the dataset provider kaggle  and the open-source community for tools that made this analysis possible.Special Thanks to **Miss Aqsa Moiz** to giving us this knowledge and skills and **S.M.I.T** to providing us the learning platform.

 ---

 ## Contact 
 Feel free to on  [Facebook](https://www.facebook.com/profile.php?id=61575636217032), [twitter/x.com] @AhmedZahabia , [Instagram](https://www.instagram.com/zahabiaahmed/) 

 ---
 ## Watch Live Stream 
 View From Here:[Live Stream](https://youtu.be/3zwiF79CwgU?si=TFUedGT_QdI9nI4t)
 View Revised version Here:[Housing_Analysis](https://youtu.be/aLuM9LZ7ArI?si=gt0_-dBvZBtnAqXI)




