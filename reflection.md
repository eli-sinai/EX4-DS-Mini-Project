## Reflection Answers

### a. What did I ask the AI coding tool to do?

I asked the tool to build a focused regression notebook for the Ames Housing data, including data loading, cleaning, feature engineering, model comparison, and an evaluation plot. One specific prompt was: “Use pandas and scikit-learn to build a clean house-price regression notebook that engineers three features, trains Ridge and Random Forest models, and returns RMSE and R2 for each model.” The tool produced a notebook structure with the required preprocessing, model training, and visualization steps.

### b. What did the tool do well? Where did it struggle, hallucinate, or produce incorrect DS code?

The tool was strong at producing an organized notebook structure and workflow. It also helped quickly draft the feature-engineering ideas and the evaluation logic. Where it struggled was in the details of the pandas and scikit-learn API usage. For example, it initially needed guidance to ensure the preprocessing pipeline handled both numeric and categorical columns correctly and that the feature split was aligned with the target column.

### c. One key takeaway about using AI in data science workflows

AI is most effective when it is used as a collaborator for structure and speed rather than a fully autonomous replacement for review. In data science, the model code and the data schema must still be checked carefully, especially around preprocessing, missing values, and train/test splits. The best results come from giving the tool clear requirements and then validating each step with the actual dataset.
