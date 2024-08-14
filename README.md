db, deployment:
https://console.choreo.dev/login

backend:
```
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python manage.py runserver
```

frontend:
```
npm install axios react-router-dom jwt-decode
npm run dev
```
