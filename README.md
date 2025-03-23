# sentiment-analysis-Classification
📌 **Text Classification with Machine Learning and Deep Learning**  

📂 **Overview**  
This project performs sentiment analysis on customer feedback using both traditional machine learning and deep learning models.  

📊 **Dataset**  
The dataset includes the following columns:  
- **Text**: Customer feedback content  
- **Sentiment**: Sentiment label (Positive, Negative)  
- **Source**: Feedback source  
- **Date/Time**: Feedback timestamp  
- **User ID**: Customer identifier  
- **Location**: Customer's location  
- **Confidence Score**: Sentiment classification confidence score  

⚙ **Installation**  
Install the required dependencies:  
```bash
pip install pandas numpy matplotlib seaborn wordcloud nltk scikit-learn torch transformers
```  

🛠 **Preprocessing**  
- Text cleaning (convert to lowercase, remove special characters, strip extra spaces)  
- Remove missing values (NaN)  

🤖 **Model Training**  
- **Traditional ML**: Logistic Regression with TF-IDF  
- **Deep Learning**: Transformer-based text classification model  

📈 **Visualization**  
A bar chart is used to display sentiment distribution.  

▶ **Usage**  
Run the Jupyter Notebook to process data, train models, and evaluate results.  

📜 **License**  
This project is licensed under the MIT License.  
