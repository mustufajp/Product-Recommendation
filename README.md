# product_recommendation

The objective of this project is to develop a recommendation system designed to predict the next item a customer might purchase, using real-world business data.

Initially, the system employs collaborative filtering, using cosine similarity, to identify relevant product categories before suggesting specific items within those categories. This approach is preferred over content-based filtering due to the unique characteristics of the men's silver accessory industry. Customers in this domain often purchase diverse items across various categories; for instance, after buying a pendant, they might opt for a ring instead of another pendant.

However, relying solely on collaborative filtering presents challenges due to the dataset's complexity—comprising over 20,000 products—and the sparsity of sales data. Therefore, to suggest specific item within the category, a product with most purchases is recommended.

In future, to improve the system further, may consider implenting hybrid system of collaborative and content based system.
