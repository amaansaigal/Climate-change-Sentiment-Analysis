# Climate-change-Sentiment-Analysis
"Climate Sentiment Analysis" utilizes N-grams and machine learning models to gauge public sentiment in climate change-related tweets. Logistic Regression, with bi-grams as input, achieves the best results. This project aids in understanding public opinions on climate change.


# Climate Sentiment Analysis

## Overview
This project focuses on analyzing sentiments related to climate change in tweets. It leverages N-grams and various machine learning models to predict sentiment labels.

## Features
- Utilizes N-grams for text preprocessing.
- Implements Logistic Regression, Linear Support Vector Classifier, Ridge Classification, Extra Trees Classification, Random Forest Classification, Decision Tree, and K Neighbors Classification models.
- Evaluates models using accuracy, recall, precision, and F1-score.
- Compares the effectiveness of different N-gram ranges.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, nltk

## How to Use
1. Clone the repository.
2. Install required libraries using `pip install -r requirements.txt`.
3. Run the Jupyter notebook `Sentiment_Analysis.ipynb` for a step-by-step guide and results.

## Results

The project presents insightful findings based on sentiment analysis of climate-related tweets. Here are key results and observations:

1. **Sentiment Distribution:** The majority of tweets were categorized as "pro" or supportive of the belief in man-made climate change. This sentiment dominated the dataset, followed by "news" tweets. "Anti" and "neutral" sentiments were less frequent.

2. **Significant Bi-Grams:** Bi-gram analysis revealed prominent word combinations. For instance, "climate change," "global warming," and "man-made climate" were frequently associated with "pro" and "news" sentiments. In contrast, "hoax" and "climate change is" often appeared in "anti" sentiments.

3. **Tri-Gram Insights:** Tri-gram analysis provided deeper context. Tri-grams like "fight climate change," "Paris Climate Agreement," and "climate change policy" appeared in "pro" sentiments, indicating discussions around climate action.

4. **Model Comparison:** Various machine learning models were evaluated, with logistic regression performing well in terms of accuracy, precision, recall, and F1-score. However, the choice of model may depend on specific use cases and requirements.

5. **N-Gram Impact:** The choice of N-grams (unigrams, bigrams, and trigrams) significantly influenced sentiment analysis results. Tri-grams often captured more nuanced sentiment expressions.

6. **Visualization:** Data visualizations, including bar charts and confusion matrices, were employed to present results and model evaluations effectively.

7. **Sector Analysis:** The project also explored energy consumption and business turnover across sectors, offering valuable insights for further analysis and decision-making.

It's important to note that these results are based on the dataset used and may vary in different contexts. Nevertheless, they provide a valuable understanding of climate sentiment on social media platforms.


## Limitations

While this project provides valuable insights into climate sentiment analysis, it has certain limitations:

1. **Data Quality:** The accuracy of sentiment analysis heavily relies on the quality and diversity of the dataset. Biases or inaccuracies in the dataset can affect the model's performance.

2. **Simplified Sentiment Classification:** The sentiment labels in this project are simplified into four categories: anti, neutral, pro, and news. Real-world sentiments are often more nuanced, and this simplification may not capture the full spectrum of opinions.

3. **Dependency on Data:** The project heavily depends on the dataset used. Different datasets may yield different results, and generalizing findings to broader contexts requires careful consideration.

4. **Fine-Tuning:** The machine learning models used in this project may not be optimized to their fullest potential. Further fine-tuning and hyperparameter optimization could potentially improve model performance.

5. **Contextual Understanding:** Sentiment analysis often struggles with understanding context. Some tweets may contain sarcasm or nuanced meanings that can be challenging for models to interpret accurately.

6. **Temporal Variations:** Public sentiment on climate change can change over time due to various events, news, or discussions. This analysis does not account for temporal variations.

7. **Bias Awareness:** The project does not explicitly address biases within the data, which could lead to skewed results. Careful bias analysis and mitigation strategies are important for robust sentiment analysis.

8. **Scaling:** For large-scale sentiment analysis tasks, more sophisticated distributed computing resources and techniques might be required.

Despite these limitations, this project serves as a valuable starting point for understanding climate sentiment on social media platforms.


Feel free to contribute and enhance the project further!
