Set-ExecutionPolicy RemoteSigned открыть повершел от админа и поставить Y вместо N
.venv\Scripts\activate
deactivate
flask --app flaskr run
python -m build --wheel
pytest
