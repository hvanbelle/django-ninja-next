# django-ninja-next

## Links
- https://www.photondesigner.com/articles/next-django-ninja
- http://localhost:8000
- http://localhost:8000/api/items
- http://localhost:3001/

## Commands
- python -m venv venv
- source venv/bin/activate
- pip install django django-ninja django-cors-headers
- pip install --upgrade pip
- pip install python-dotenv
- pip freeze > requirements.txt 
- django-admin startproject core .
- python manage.py startapp api
- python manage.py makemigrations
- python manage.py migrate
- python manage.py createsuperuser --username admin --email admin@home.arpa
- python manage.py runserver
- npx create-next-app@latest ivy
- python manage.py shell

## Data to import
```
from api.models import Item
Item.objects.create(name="Item 1", description="This is the first item.")
Item.objects.create(name="Item 2", description="This is the second item.")
Item.objects.create(name="Item 3", description="This is the third item.")
Item.objects.create(name="Item 4", description="This is the fourth item.")
Item.objects.create(name="Item 5", description="This is the fifth item.")
Item.objects.create(name="Item 6", description="This is the sixth item.")
print("Sample items created successfully!")
```


