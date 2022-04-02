## Script for automation Horizontal Pod Autoscaling (HPA) creating

Create Virtualenv first
```shell
python3 -m venv .venv
```

Than activate .venv 
```shell
source .venv/bin/activate
```
After activate .venv, Install python client for the kubernetes API
```shell
pip install kubernetes
```

Run script
```shell
python create_hpa.py
```

After making preparations to work, get information [about HPA](https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale/). 

