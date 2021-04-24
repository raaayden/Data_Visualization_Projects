Install
1. Create a virtual env
    - mkdir smc-dashboard
    - cd smc-dashboard
    - py -3 -m venv dv
    - cd dv/scripts
    - activate

2. Install requirements
    - pip install -r requirements.txt 
    or
    - pip install flask
    - pip install flask-bootstrap

Access
cd app
set FLASK_ENV=development
set FLASK_APP=app.py
flask run