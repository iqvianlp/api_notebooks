# API Marketplace Demo
## IQVIA NLP API Notebooks

Example Jupyter Notebooks for interacting with IQVIA NLP APIs.
These Notebooks are designed for users to interact with the IQVIA NLPs programmatically.
These are simple code examples that can be used out of the box with valid IQVIA API Marketplace credentials.

Each notebook serves a specific IQVIA NLP Endpoint.

## Prerequisites
* Python 3.8
  - Use the command to make sure you have correct version of Python installed:
    - $ python -V
  - Recommending creating a virtualenv with Python 3.8 to keep your system packages clean. You could create the virtualenv with this command: 
      - $ python -m venv <path_to_your_new_venv>
  - Activate the virtualenv with this command:
    - Windows: $ <path_to_your_new_venv>/Scripts/activate
    - Centos 7: $ source <path_to_your_new_venv>/bin/activate   
* Installed all packages in requirements.txt: 
  - $ pip install -r requirements.txt
* Registered user on https://api-marketplace.work.iqvia.com/s/
* Subscribed to your desired NLP API, and already got the client id and client secret for your desired NLP API application (view it under "Licenses")

## Quick start
Launch the jupyter notebook of your interest, and follow it step-by-step.
* To launch the jupyter notebook: 
  - Activate the virtualenv:
    - Windows: $ <path_to_your_new_venv>/Scripts/activate
    - Centos 7: $ source <path_to_your_new_venv>/bin/activate  
  - Launch: $ jupyter notebook
* To stop jupyter notebook from running:
  - clicking "QUIT" button at the top right of the dashboard
  - Or press CTRL+C
  - Or run $ jupyter notebook stop 8888
* Deactivate virtualenv:
  - $ deactivate

## Feedback
Please contact hui.feng@iqvia.com