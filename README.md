# Product Recommendation System

The objective of this project is to develop a recommendation system designed to predict the next item a customer might purchase, using real-world business data from the men's silver accessory industry.

## Overview

This recommendation system employs collaborative filtering with cosine similarity to identify relevant product categories before suggesting specific items within those categories. Unlike content-based filtering, which may not suit this industry due to the diverse purchasing patterns observed (e.g., customers buying different types of items after purchasing a specific product like a pendant), collaborative filtering is preferred.

### Challenges

The dataset used in this project comprises over 20,000 products, leading to challenges related to data complexity and sparse sales data. To address these challenges, the system suggests the most purchased item within a recommended category.

## Future Enhancements

In the future, the system could be enhanced by implementing a hybrid recommendation approach that combines collaborative filtering with content-based filtering. This hybrid system aims to leverage the strengths of both approaches for more accurate and personalized recommendations.

## Technologies Used

- Python
- Collaborative filtering (cosine similarity)
- Pandas
- Scikit-learn
