# Description
A music controller app, to vote for skipping a song or add a new one.

# Setup
- ``python -m venv .env``
- ``.env/Scripts/activate``
- ``pip install django djangorestframework``
- ``django-admin startproject music_controller``
- ``cd music_controller``
- ``python manage.py startapp api``

# Save
- ``python manage.py makemigrations``
- ``python manage.py migrate``
