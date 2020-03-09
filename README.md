|             | status |
|-------------|------------|
| **master** | [![Build Status](https://travis-ci.org/juancra264/flask_template.svg?branch=master)](https://travis-ci.org/juancra264/flask_template) [![Coverage Status](https://coveralls.io/repos/github/juancra264/flask_template/badge.svg?branch=master)](https://coveralls.io/github/juancra264/flask_template?branch=master)

# Python 3 - Flask Template

> Python Flask template

## Quick Start

```bash
# Add your DATABASE URI in app.py and your mail params in send_mail.py

# Install dependencies
pipenv shell
pipenv install

# Serve on localhost:5000

```
pipenv run gunicorn --config gunicorn.py run:app