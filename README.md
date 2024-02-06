# NLP-on-consumer-compliants



**Project Title: Customer Complaint Analysis for Bank**

**Overview:**
The "Customer Complaint Analysis for Bank" project aims to leverage natural language processing (NLP) techniques to analyze and categorize customer complaints received by a bank. The dataset comprises various features such as Date received, Product, Sub-product, Issue, Sub-issue, Consumer complaint narrative, Company public response, Company, State, ZIP code, Tags, Consumer consent provided?, Submitted via, Date sent to the company, Company response to consumer, Timely response? Consumer disputed?, Complaint ID. The project employs data cleaning, preprocessing, scaling, and visualizations to understand and categorize customer complaints accurately.

**Key Features:**

1. **Data Collection and Cleaning:**
   - Compiled a comprehensive dataset containing customer complaints related to various banking products and services.
   - Applied data cleaning techniques to handle missing values, outliers, and inconsistencies in the dataset.
   - Ensured the data's integrity and reliability for subsequent analysis.

2. **Data Preprocessing and Scaling:**
   - Utilized NLP techniques for processing textual data in the "Consumer complaint narrative" feature.
   - Preprocessed the text data by tokenization, removing stop words, and converting text to numerical representation.
   - Scaled numerical features to ensure uniformity in data distribution.

3. **Visualization:**
   - Employed data visualization techniques to gain insights into the distribution of complaints across different products, issues, and regions.
   - Visualized the processed text data to understand prevalent themes and patterns in customer narratives.

4. **Model Architecture:**
   - Constructed a neural network model using Sequential architecture for complaint categorization.
   - Utilized Dense layers with ReLU activation functions to capture complex relationships in the data.
   - Incorporated Dropout layers to prevent overfitting.
   - Applied Softmax activation in the output layer for multiclass classification.

5. **Model Training:**
   - Compiled the model with categorical cross-entropy loss and the Adam optimizer.
   - Trained the model on the preprocessed dataset to learn patterns and associations between textual features and complaint categories.
   - Evaluated the model's performance using accuracy as a metric.

6. **Prediction and Analysis:**
   - Predicted the type of complaint a customer has based on the NLP analysis of their narratives.
   - Analyzed model predictions and identified areas for improvement or refinement.

**Conclusion:**
The "Customer Complaint Analysis for Bank" project offers a robust approach to understanding and categorizing customer complaints through the application of natural language processing and neural network modelling. By extracting insights from customer narratives, the project provides the bank with a tool to efficiently address customer concerns, improve service quality, and enhance overall customer satisfaction. The model's ability to categorize complaints aids in streamlining customer support processes and contributes to the bank's continuous improvement initiatives. This project establishes the foundation for further advancements in customer complaint analysis and reinforces the importance of leveraging technology for proactive customer engagement.
