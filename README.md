# terraform-python-flask-app

Set project
Set permission
Enable below permission
- compute.instance.*
- compute.firewalls.*
Enable the Compute Engine and OS Login APIs.
Start Cloud Shell
mkdir terraform-tutorial 
cd terraform-tutorial
nano main.tf
use main.tf file in git repo to deploy vm

terraform init
terraform plan
terraform apply

This deploys the VM in GCP and opens ports

ssh into the VM

build flask app

mkdir myproject
cd myproject
nano app.py
paste app.py repo code to this file
pip install flask
python3 -m venv venv
. venv/bin/activate
python app.py

ssh into the vm and paste
curl http://0.0.0.0:5000        > able to see output hello world

last able to destroy

terraform destroy

