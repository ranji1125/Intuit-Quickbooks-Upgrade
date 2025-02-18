# Intuit-Quickbooks-Upgrade

## Project Description
In this extensive project, I was tasked with the development of predictive models aimed at targeting businesses for an upsell campaign of Intuit's QuickBooks software. The challenge was to pinpoint which of the 75,000 businesses, previously unresponsive in the first marketing attempt, might engage in a second wave. The provided dataset, stored in a Parquet file, encompassed various business attributes and initial response data. My role involved data preprocessing, crafting predictive models using logistic regression and neural networks, and estimating the potential profit from targeting specific businesses for the campaign's second phase.

## Technology Stack
- **Data Analysis and Modeling**: Python, pandas, scikit-learn, pyrsm
- **Data Visualization**: Matplotlib
- **Version Control**: Git and GitHub for collaborative coding and version management

## Key Accomplishments

### Data Preprocessing
- **Encoding and Standardization**: Implemented one-hot encoding for categorical variables and standardized features to normalize model input.

### Predictive Modeling
- **Model Development**: Created models using logistic regression and neural networks to forecast response probabilities for the upcoming campaign wave.
- **Feature Selection**: Applied Lasso regression to select significant features, enhancing both the accuracy and interpretability of the models.

### Model Evaluation and Selection
- **Testing and Validation**: Extensively tested and validated models, utilizing AUC metrics for performance comparison.
- **Hyperparameter Optimization**: Used GridSearchCV to fine-tune neural network parameters, optimizing model architectures.

### Profit Estimation
- **Revenue Calculation**: Estimated potential profits by considering mailing costs and anticipated revenue from successful business upsells.
- **Targeting Strategy**: Devised a targeting strategy based on predictive probabilities and break-even analysis, focusing on the most likely responders.

### Report and Documentation
- **Comprehensive Reporting**: Compiled a detailed report outlining methodologies, model performance, and the strategic implications of the findings.
- **Reproducibility**: Ensured result reproducibility with thorough documentation in a Jupyter Notebook and maintained the codebase on GitHub.

## Key Outcomes
- **Improved Targeting Efficiency**: Enhanced the precision of business targeting, potentially boosting the ROI of the upsell campaign.
- **Data-Driven Decision Making**: Facilitated a data-oriented approach to campaign management by quantifying the influence of various business attributes on customer responsiveness.
- **Scalability and Adaptability**: Established a flexible and scalable modeling framework, readily adaptable to future marketing initiatives under varying conditions.
