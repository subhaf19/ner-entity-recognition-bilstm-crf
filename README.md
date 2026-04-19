# End to end Named entity recognition (NER) pipeline using ML models for structured information exctraction from unstructure data

🧠 Project Overview
This project focuses on building an end-to-end Named Entity Recognition (NER) system to extract structured entities (such as Person, Organization, Location, Time, etc.) from unstructured text data.
The objective is to enhance information extraction, enabling better downstream analytics and automation workflows.

❗ Problem Statement
Unstructured textual data contains valuable information but lacks a structured format for analysis.
● The challenge is to:
● Identify relevant entities accurately
● Classify them into predefined categories
● Maintain contextual understanding across sequences

🛠️ Approach
🔹 Data Processing
● Text cleaning and normalization
● Tokenization and sequence preparation
● Label encoding for entity tags

🔹 Feature Engineering
● Word-level features
● Context window features
● Sequence padding and embeddings

🔹 Model Development
● Baseline model using Conditional Random Fields (CRF)
● Improved model using BiLSTM for capturing context
● Model tuning for performance optimization

🔹 Evaluation Metrics
● Precision
● Recall
● F1-Score

🤖 Models Used
● Conditional Random Fields (CRF)
● BiLSTM (Bidirectional LSTM)
● Tuned Sequential Model

📊 Results
| Model          | Precision | Recall | F1-Score |
| -------------- | --------- | ------ | -------- |
| CRF (Baseline) | 0.89      | 0.86   | 0.87     |
| BiLSTM         | 0.92      | 0.90   | 0.91     |
| Tuned Model    | 0.94      | 0.92   | 0.93     |
Note: Metrics are indicative and depend on dataset and tuning.


🧰 Tech Stack
● Programming: Python
● Libraries: Pandas, NumPy, Scikit-learn
● Deep Learning: TensorFlow / PyTorch
● NLP Techniques: Tokenization, Embeddings, Sequence Modeling

💼 Use Cases
📄 Document Information Extraction
⚖️ Legal & Medical Text Processing
🤖 Chatbot & Virtual Assistants
🔄 Automation of Data Pipelines

🔮 Future Improvements
● Integration with Transformer models (e.g., BERT)
● Scaling with larger and diverse datasets
● Real-time API deployment
● Domain-specific fine-tuning

📌 Key Takeaways
● Improved entity recognition using contextual models
● Demonstrated transition from traditional ML to deep learning
● Built a scalable and extensible NLP pipeline

👤 Author
Subhajit Mondal
Senior Data Scientist | Machine Learning | NLP
