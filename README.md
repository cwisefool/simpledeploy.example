# diydeploy.example
Repository used for demonstrating how to perform a simple deploy using only Git and a small custom shell script. 
See deploy.sh for full deployment process. Deployment process automatically pulls latest version of this repository. 

- Installs Apache2 web server
- Everything in `html` is deployed to `/var/www/html`. 

## Installation
Simply git clone into desired directory. 

Ex: `git clone https://github.com/cwisefool/simpledeploy.example.git simpledeploy.example`

## Deployment
From within cloned directory:

`bash deploy.sh`

