# Classification_Pipeline



// Description
This project implements a modular machine learning pipeline for classification tasks
using object-oriented programming and comparing the performance of various algorithms:

* XGBoost
* Random Forest
* CatBoost

// Key Features
* **OOP Design:** Clear, maintainable, and reusable code
* **Modular Components:** Easy modification and extension
* **Algorithm Comparison:** Insights into strengths and weaknesses
* **Detailed Reports:** Execution, results, comparisons
* **Flexible:** Accommodates various datasets and problems

// Installation
1. Clone the repository: `git clone https://github.com/your-username/classification-pipeline.git`
2. Install dependencies: `pip install -r requirements.txt`

// Usage
1. Prepare your dataset (supported formats: CSV, XGBoost DMatrix)
2. Run the pipeline:

```dm
from pipeline import ClassificationPipeline

pipeline = ClassificationPipeline(
    data_path = "path/to/your/dataset.csv",
    target_column = "target_column_name",
    algorithms = ["xgboost", "random_forest", "catboost"],
    report_path = "results.txt"
)

pipeline.run()
