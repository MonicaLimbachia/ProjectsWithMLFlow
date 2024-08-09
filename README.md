## ML Flow Experiments
Copy,paste  and run the following code in your python enviroment to see the model.

import dagshub
dagshub.init(repo_owner='MonicaLimbachia', repo_name='ProjectsWithMLFlow', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)