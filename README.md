# Backend
In music-app/

- ``python -m venv .env``
- ``.env/Scripts/activate``
- ``pip install django djangorestframework``
- ``django-admin startproject music_controller``
- ``django-admin startapp api``

# Frontend
In music-app/music_controller/frontend/

- ``npm i webpack webpack-cli --save-dev``
- ``npm i @babel/core babel-loader @babel/preset-env @babel/preset-react --save-cli``
- ``npm install react@17 react-dom@17 --save-dev``
- ``npm install @material-ui/core``
- ``npm install @babel/plugin-proposal-class-properties``
- ``npm install react-router-dom@5``
- ``npm install @material-ui/icons``

# Backend Run
- ``python manage.py makemigrations``
- ``python manage.py migrate``
- ``python manage.py runserver``

# Frontend Run
In music-app/music_controller/frontend/
- ``npm run dev``