#Managing the end-to-end machine learning lifecycle with MLFlow

This Repository contains a handson walkthrough of managing an end to end ML lifecycle using MLFlow

##Basic setup

- Create a virtual environment

```
conda create --name myenv
```

activate the env:

```
conda activate myenv
```

- Install the packages

```
pip install -r requirements.txt
```


##Start the MLFlow server

use the following command in the terminal

```
mlflow server --backend-store-uri mlruns/ --default-artifact-root mlruns/ --host 127.0.0.1 --port 5000
```

Visit 127.0.0.1:5000 to access the mlflow UI

