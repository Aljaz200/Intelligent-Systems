# Intelligent Systems

Coursework for the Intelligent Systems course at the Faculty of Computer and Information Science, University of Ljubljana, 2024/25:

- 10 laboratory exercises covering foundational and advanced topics in artificial intelligence.
- 2 seminar projects focusing on optimization and natural language processing (NLP).

## List of Completed Laboratory Exercises:

---

- **Lab 1**: Data Wrangling
- **Lab 2**: Genetic Algorithms
- **Lab 3**: Visualization
- **Lab 4**: Classification
- **Lab 5**: Supervised learning, cross-validation, hyperparameter tuning
- **Lab 6**: Attribute Evaluation (Feature selection)
- **Lab 7**: Natural language processing (NLP)
- **Lab 8**: Clustering, Ensemble Learning
- **Lab 9**: Deep Learning
- **Lab 10**: Reinforcement Learning

## Seminar Projects:

### Seminar 1: Optimizing Conference Paper Assignment Using Genetic Algorithms

**Objective**:\
The goal of this seminar was to design a system to optimize the assignment of conference papers to reviewers using genetic algorithms. The solution had to maximize overall satisfaction by aligning reviewer preferences while meeting specific constraints.

**Key Tasks**:

- **Representation**: Develop a data structure and representation for reviewer-paper assignments, considering preferences, friendship constraints, and authorship restrictions.
- **Crossover and Mutation**: Customize genetic algorithm operations to ensure constraint satisfaction and generate valid solutions.
- **Diversity and Complexity**: Introduce mechanisms to explore diverse and complex solutions, penalizing constraint violations.
- **Evaluation**: Conduct experiments to compare the performance of different configurations and provide a detailed analysis of results.

---

### Seminar 2: Text Classification for Emotion Detection

**Objective**:\
The aim of this seminar was to train and evaluate an NLP classification model capable of detecting six emotions (sadness, joy, love, anger, fear, surprise) in text.

**Key Tasks**:

- **Data Preparation and Exploration**: Process the dataset, handle missing values, analyze class distributions, and prepare data for machine learning.
- **Basic Machine Learning**: Train and evaluate standard ML models (e.g., decision trees, random forests) with hyperparameter tuning and cross-validation.
- **Advanced Machine Learning**: Experiment with advanced NLP techniques, including neural networks, pre-trained embeddings, fine-tuning, and ensemble models. Extend the dataset by incorporating additional data and analyze its impact.
- **Evaluation and Reporting**: Compare the performance of various models and configurations using clear visualizations and analysis.

---

### Installing Required Libraries:

To install the necessary dependencies, run:

```bash
pip install -r requirements.txt
```