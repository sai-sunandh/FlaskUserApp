Virtual Environment Commands

pip install virtualenv


python -m venv 'virtual env name'  ## virtualenv <v env name>

.\<vir name>\Scripts\Activate      ### source .\<v name>\bin\activate



pip install flask flask-sqlalchemy


>>> from a import app, db
>>> with app.app_context():
...     db.create_all()
