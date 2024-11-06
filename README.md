# Setup
In music-app/

- ``python -m venv .env``
- ``.env/Scripts/activate``
- ``pip install django djangorestframework``

In music-app/music_controller/frontend/

- ``npm i webpack webpack-cli --save-dev``
- ``npm i @babel/core babel-loader @babel/preset-env @babel/preset-react --save-cli``
- ``npm install react@17 react-dom@17 --save-dev``
- ``npm install @material-ui/core``
- ``npm install @babel/plugin-proposal-class-properties``
- ``npm install react-router-dom``
- ``npm install @material-ui/icons``

# Other Setup
- ``django-admin startproject music_controller``
- ``django-admin startapp api``
- ``python manage.py makemigrations``
- ``python manage.py migrate``
- ``python manage.py runserver``