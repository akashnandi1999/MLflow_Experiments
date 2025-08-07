## ML FLow experiements

import dagshub
dagshub.init(repo_owner='akashnandi1999', repo_name='MLflow_Experiments', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)

Token = c5766a12ee0830fec6c681e73817bcc3caa53355
Dagshub_URL = https://dagshub.com/akashnandi1999/MLflow_Experiments.mlflow