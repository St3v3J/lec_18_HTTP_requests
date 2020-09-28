How to run tests
Install PyTest: pip install pytest
Make sure you have __init__.py in the tests folder
Run: pytest -p no:warnings
Be aware that tests will use your default localhost (TinyDB) database and also purge it in the end.