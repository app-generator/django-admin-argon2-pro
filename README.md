# **[Django Admin Argon2 PRO](https://appseed.us/product/argon-dashboard2-pro/django/)**

**Django** starter styled with **[Admin Argon PRO](https://appseed.us/product/argon-dashboard2-pro/django/)**, a premium `Boostrap 5` design from [Creative-Tim](https://bit.ly/3fKQZaL)
The product is designed to deliver the best possible user experience with highly customizable feature-rich pages. 

> 👉 **NOTE**: This product `requires a License` in order to access the theme:

**Private REPO**: `git+https://github.com/app-generator/priv-django-admin-argon2-pro`

<br />

## Features: 

- **UI Kit**: Argon Dashboard BS5 PRO `v2.0.5` by Creative-Tim
- [Django Argon2 PRO](https://github.com/app-generator/django-argon-dashboard2-pro) - `sample project`
- **Sections Covered**: 
  - `Admin Section`, reserved for `superusers`
  - `All pages` managed by `Django.contrib.AUTH`
  - `Registration` page
  - `Misc pages`: colors, icons, typography, blank-page 

<br />

![Argon Dashboard 2 PRO - Charts Page (Premium Bootstrap 5 Design)](https://user-images.githubusercontent.com/51070104/211157993-fd439b20-6117-4e02-b98c-9123866660e2.jpg)

<br />

## Why `Django Admin Argon PRO`

- Modern [Bootstrap 5](https://www.admin-dashboards.com/bootstrap-5-templates/) Design
- `Responsive Interface`
- `Minimal Template` overriding
- `Easy integration`

Argon Dashboard 2 PRO makes use of light, surface and movement. The general layout comes with two modes: Light & Dark. Inside the archive you will find multiple example pages on how to use all components. And, of course, every element is documented.

<br />

## How to use it

<br />

> **Install the package** via `PIP` 

```bash
$ pip install git+https://github.com/app-generator/priv-django-admin-argon2-pro.git
```

<br />

> Add `admin_argon2_pro` application to the `INSTALLED_APPS` setting of your Django project `settings.py` file (note it should be before `django.contrib.admin`):

```python
    INSTALLED_APPS = (
        ...
        'admin_argon2_pro.apps.AdminArgon2ProConfig',
        'django.contrib.admin',
    )
```

<br />

> Add `LOGIN_REDIRECT_URL` and `EMAIL_BACKEND` of your Django project `settings.py` file:

```python
    LOGIN_REDIRECT_URL = '/'
    # EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'
    EMAIL_BACKEND = 'django.core.mail.backends.console.EmailBackend'
```

<br />

> Add `admin_argon2_pro` urls in your Django Project `urls.py` file

```python
    from django.urls import path, include

    urlpatterns = [
        ...
        path('', include('admin_argon2_pro.urls')),
    ]
```

<br />

> **Collect static** if you are in `production environment`:

```bash
$ python manage.py collectstatic
```

<br />

> **Start the app**

```bash
$ # Set up the database
$ python manage.py makemigrations
$ python manage.py migrate
$
$ # Create the superuser
$ python manage.py createsuperuser
$
$ # Start the application (development mode)
$ python manage.py runserver # default port 8000
```

Access the `admin` section in the browser: `http://127.0.0.1:8000/`

<br />

## Screenshots

![Argon Dashboard 2 PRO - Automotive (Premium Bootstrap 5 Design).](https://user-images.githubusercontent.com/51070104/211158013-fea76b79-bb54-4066-a617-5ec3b4b6ec42.jpg)

<br />

> [Django Argon2 PRO](https://appseed.us/product/argon-dashboard2-pro/django/) - `Charts` Page

![Argon Dashboard 2 PRO - Charts (Premium Bootstrap 5 Design).](https://user-images.githubusercontent.com/51070104/211158055-f29b86dd-0119-433c-af02-5bb41c041049.jpg)

<br />

> [Django Argon2 PRO](https://appseed.us/product/argon-dashboard2-pro/django/) - `eCommerce` Product Page

![Argon Dashboard 2 PRO - eCommerce (Premium Bootstrap 5 Design).](https://user-images.githubusercontent.com/51070104/211158098-afc2b3a6-0c2e-47ea-80d1-c26db0e80da1.jpg)

<br />

---
**[Django Admin Argon2 PRO](https://appseed.us/product/argon-dashboard2-pro/django/)** - Modern Admin Interface provided by **[AppSeed](https://appseed.us/)**
