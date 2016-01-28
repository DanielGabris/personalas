Personal Authorization Server

Prerequisite:
- Python3.4
- pip3

Installation Guide:

1. Install necessary packages by running following command:
pip install -r requirement.txt
python3 manage.py migrate
python3 manage.py createsuperuser

2. Change settings.py with credentials:
Replace fields OIDC_DYNAMIC_CLIENT_REGISTRATION_DATA, OIDC_DEFAULT_BEHAVIOUR, OIDC_PROVIDERS with your credentials

3. Launch server by the following command:
python3 manage.py runserver
