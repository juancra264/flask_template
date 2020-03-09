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