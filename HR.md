python3 -m venv env
Set-ExecutionPolicy Unrestricted -Scope Process
env\scripts\activate
pip install -r requirements.txt
$env:FLASK_APP = "main"
flask run