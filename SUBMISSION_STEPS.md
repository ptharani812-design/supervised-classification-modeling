# How to run and submit Task 04

1. Download and extract `Task04_Supervised_Modeling.zip`.
2. Open [Google Colab](https://colab.research.google.com/).
3. Choose **File → Upload notebook** and select `Supervised_Classification_Modeling_Tuning.ipynb`.
4. In Colab, open the **Files** panel and upload `customer-churn-training.csv` from your Task 03 project. Do not upload sensitive data to a public repository unless you have permission.
5. Run the notebook cells from top to bottom. If prompted that a library is missing, run `!pip install -r requirements.txt` in a cell (or install the listed packages).
6. Check the model comparison table, metrics, confusion matrix, and ROC-AUC curve (if both classes are present in the test set).
7. The final cells create `best_churn_model.joblib`. Download it from the Colab Files panel if your submission asks for the serialized model.
8. For a public link, create a GitHub repository and upload the notebook, README, requirements, and submission instructions. Only upload the CSV if you have permission to share it publicly. Otherwise, leave it out and ensure your instructor can access the data separately.
9. Copy the GitHub repository URL and paste it into the task portal using **Submit deliverable**.

**Note:** The supplied dataset has only 12 rows. The results are for learning purposes and must not be presented as production-ready.
