# Airline Review Analysis

## 📝 Project Background

This project was developed during a Forage virtual work experience simulation, which I successfully completed. However, just before submission, the original module was updated and is no longer accessible in its previous form. While the specific task has been updated or removed from the platform, this implementation reflects the full scope of my independent work and skills applied during that experience.

The app processes airline review data, classifies sentiment using natural language processing techniques, and displays results through a Streamlit interface.

## 📌 Disclaimer

This project was developed solely for **educational and portfolio** purposes as part of a **Forage virtual experience program**, which provided permission to use a sample dataset for learning exercises.

- This repository is **not affiliated with any airline or commercial entity**.
- No personally identifiable information (PII) was collected, stored, or used.
- The data used in this project was either simulated or explicitly permitted for educational use.
- Please do not use this project or its contents to scrape or extract data from live websites without appropriate permissions and compliance with applicable data protection laws (e.g., GDPR, CCPA).

By using or referencing this repository, you acknowledge and accept these conditions.


### 🚀 Key Features
- Text preprocessing and TF-IDF vectorization
- Automatic sentiment labeling using NLTK's VADER
- Supervised learning with Logistic Regression and SVM
- Deployment via Streamlit for interactive use
- Emphasis on data ethics and privacy compliance

## 📊 Data Source

Customer reviews were programmatically scraped from [airlinequality.com](https://www.airlinequality.com/). The dataset comprises reviews collected from the first 1000 pages.

## 🛠️ Methodology

1. **Data Acquisition:** The `BeautifulSoup` library was used to parse HTML content and extract review details (e.g., review text, overall rating, aspect ratings, recommendation status) from `airlinequality.com`.

2. **Data Storage:** Scraped data was structured and stored efficiently, typically in a Pandas DataFrame.

3. **Sentiment Analysis:** NLTK's VADER (Valence Aware Dictionary and sEntiment Reasoner) was employed to classify review texts into positive, negative, and neutral sentiments based on their compound scores.

4. **Quantitative Analysis:** Statistical methods were applied to analyze numerical ratings and categorical data.

5. **Visualization:** `Matplotlib` and `Seaborn` were used to create a variety of plots for data exploration and presentation of insights.

## 📈 Key Metrics Analyzed

* **Overall Satisfaction Score:** Average rating and distribution of customer satisfaction.

* **Sentiment Score:** Distribution of positive, negative, and neutral sentiments derived from review texts.

* **Aspect-Specific Ratings:** Average ratings for different service aspects like seat comfort, food & beverages, cabin crew service, etc.

* **Frequency of Keywords/Topics:** Identification of frequently mentioned terms in reviews.

* **Review Volume Over Time:** Trends in the number of reviews submitted over yearly periods.

* **Recommendation Rate:** Percentage of customers who would recommend British Airways (based on 'True'/'false' responses).

## 📉 Visualizations Used

* **Bar Charts:** For distributions (e.g., overall ratings, sentiment categories) and comparisons (e.g., average aspect ratings).

* **Pie Charts:** To show proportions (e.g., sentiment distribution, recommendation rate).

* **Line Charts:** For visualizing trends over time (e.g., review volume).

* **Histograms:** To display the distribution of continuous variables (e.g., VADER compound scores).

* **Word Clouds:** For a quick visual representation of the most frequent words in reviews.

* **Stacked Bar Charts:** To compare proportions across different categories (e.g., recommendation rate by cabin class, sentiment distribution by recommendation group).

* **Box Plots:** To show the distribution of ratings across different groups (e.g., overall rating by recommendation status).

## 💻 Technologies Used

* **Python 3.x**

* **Pandas:** For data manipulation and analysis.

* **Beautiful Soup 4:** For web scraping.

* **NLTK:** Specifically, VADER for sentiment analysis.

* **Matplotlib:** For static plotting.

* **Seaborn:** For enhanced statistical data visualization.

* **WordCloud:** For generating word cloud visualizations.

## ▶️ How to Run

1. **Clone the repository:**

   ```
   git clone https://github.com/ubahjjohnson/airlines-review-sentiment-analysis.git
   cd airlines-review-sentiment-analysis
   
   ```

2. **Install dependencies:**

   ```
   pip install -r requirements.txt
   # Or manually:
   # pip install pandas beautifulsoup4 nltk matplotlib seaborn wordcloud
   
   ```

3. **Download NLTK VADER lexicon:**

   ```
   import nltk
   nltk.download('vader_lexicon')
   
   ```

4. **Execute the scraping script and Analysis Script**:

   ```
   python Airline-Reviews-Analysis.ipynb
   
   ```

   *(Note: The scraping process for 1000 pages can take a significant amount of time and may require handling rate limits or IP blocking. Ensure ethical scraping practices.)*


## 📧 Contact

For any questions or collaborations, please contact [e-mail](mailto:ubahjohnson@gmail.com) or connect on [LinkedIn](https://www.linkedin.com/in/johnson-ubah).
