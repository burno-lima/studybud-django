# studybud-django

![img](https://user-images.githubusercontent.com/80166382/187489574-4e4257a8-4290-49ff-8b0d-ac063d49bf30.png)

Installation

- First clone the project.

```sh
git clone https://github.com/burno-lima/studybud-django.git
```

- Create venv and activate.

```sh
python -m venv .venv
```
```sh
.venv\Scripts\activate
```
- Install dependency for project.

```sh
pip install -r requirements.txt
```

- Perform pending migration.

```sh
python manage.py migrate
```

- Create superuser.

```sh
python manage.py createsuperuser --username="admin" --email="admin@email.com"
```

- Start server.

```sh
python manage.py runserver
```
- Access

<code><a href="http://127.0.0.1:8000">127.0.0.1:8000</a></code>

