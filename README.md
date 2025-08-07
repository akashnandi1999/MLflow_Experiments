## ML FLow experiements

import dagshub
dagshub.init(repo_owner='akashnandi1999', repo_name='MLflow_Experiments', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)
