Set-ExecutionPolicy RemoteSigned
.venv\Scripts\activate
deactivate
flask --app flaskr run
python -m build --wheel
pytest
