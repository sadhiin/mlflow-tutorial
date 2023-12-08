# Wine Quality Prediction with MLflow and Dagshub (Tutorial)

This repository demonstrates a professional MLOps workflow for predicting wine quality using machine learning. It leverages MLflow for efficient model logging, tracking, and artifact management, while leveraging Dagshub for seamless collaboration and interactive visualization of your model development process.

## Getting Started:
Crete a virtual environment
```bash
conda create -n YOUR_ENV_NAME python==3.10
```

Clone this repository:
```Bash
git clone git@github.com/your-username/wine-quality-prediction.git
```
Install project dependencies:
```Bash
pip install -r requrement.txt
```

Create a Dagshub account and login:
- Create Dagshub account
- Connect with github
- Connect the project
- **Export your Experiments Credentials**

**Run on git bash / linxu distro cmd**
```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/username/repor_name.mlflow
export MLFLOW_TRACKING_USERNAME=Your_user_name
export MLFLOW_TRACKING_PASSWORD=your_token

```
Run the pipeline:
```Bash
python app.py
```

### Workflow:

Data Acquisition: Download and pre-process the public wine quality dataset.
Feature Engineering: Extract and transform relevant features for model training.
Model Training: Train a linear regression model to predict wine quality.
Model Evaluation: Evaluate the model's performance using standard metrics.
Model Deployment: Deploy the model to production for real-world predictions (optional).
Benefits:

Enhanced Reproducibility: Track and compare model runs with detailed logging and artifact management.
Comprehensive Visualization: Visualize key metrics and model performance through interactive dashboards within Dagshub.
Streamlined Collaboration: Share, discuss, and collaborate on your ML workflow with team members using Dagshub's collaborative features.
Note:

This repository provides a basic example of an MLOps workflow for wine quality prediction. Feel free to customize and extend it to optimize your own machine learning projects.