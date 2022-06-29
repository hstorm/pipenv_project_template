# https://sourcery.ai/blog/python-best-practices/

$ pip install pipenv
$ pipenv --python 3.7

# Show venv path
$ pipenv --venv
# => use the past to set python interpreter in vs-code

# activate venv
$ pipenv shell

# Install packages
$ pipenv install pandas
$ pipenv install ipykernel --dev

# Export venv requirments
$ pipenv lock -r > requirements.txt