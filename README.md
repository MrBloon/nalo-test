[![Django Version](https://img.shields.io/badge/django-4.2-green.svg)](https://docs.djangoproject.com/en/3.2/)
[![Django REST framework](https://img.shields.io/badge/django--rest--framework-3.14-green.svg)](https://www.django-rest-framework.org/)
[![pytest](https://img.shields.io/badge/pytest-7.3.1-green.svg)](https://docs.pytest.org/en/stable/)


# ice-cream-shop

A project to automate icecream orders. A user can order several scoops of different ice cream flavor and an admin can manage ice cream tubs stock
## Run Locally

Clone the project

```bash
  git clone https://github.com/MrBloon/nalo-test.git
```

Go to the project directory

```bash
  cd nalo-test
```

Install dependencies

```bash
  pipenv install
```

Create flavors and stocks

```bash
  bash icecreamshop/scripts/create_db_test.sh
```


Start the Django server

```bash
  pipenv run api/coronavstech/manage.py runserver
```

## Admin back office

To go to the back office, start the Django server and go to:
`http://localhost:8000/admin`


Enter the username and password:
`nalo_admin`
`nalo2023`
