## Virtual env

### Install virtual env

Mac OS\
`python3 -m venv venv`

Windows\
`py -3 -m venv venv`

### Activate

Mac OS\
`. venv/bin/activate` or `. venv/bin/activate.fish`

Windows\
`venv\Scripts\activate`

### Deactivate

`deactivate`

### Freeze dependencies

`pip freeze > requirements.txt`

### Install dependencies

`pip install -r requirements.txt`

## Launch

Mac OS\
`export FLASK_APP=setup.py`\
`flask run`

Windows\
`set FLASK_APP=setup.py` or for PowerShell `$env:FLASK_APP='setup.py'`\
`flask run`

To make server publicly available\
`flask run --host=0.0.0.0`

## Debug mode

Activates debugger, automatic reloader\
`export FLASK_ENV=development` or enable debug only:\
`export FLASK_DEBUG=1`
