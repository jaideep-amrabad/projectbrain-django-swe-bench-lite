# Community 576

> 16 nodes · cohesion 0.14

## Key Concepts

- **RemoteUserBackend** (12 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **.authenticate()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **CustomRemoteUserBackend** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **.clean_username()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **.configure_user()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **RemoteUserNoCreateBackend** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **.clean_username()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **.configure_user()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **This backend is to be used in conjunction with the ``RemoteUserMiddleware``…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **The username passed as ``remote_user`` is considered trusted. Return the…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **Perform any cleaning on the "username" prior to using it to get or create the…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **Configure a user after creation and return the updated user. By default, return…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **Backend that doesn't create unknown users.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **Backend that overrides RemoteUserBackend methods.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **Grabs username before the @ character.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **Sets user's email address using the email specified in an HTTP header.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`

## Relationships

- [Community 509](Community_509.md) (4 shared connections)
- [Community 101](Community_101.md) (3 shared connections)
- [Community 71](Community_71.md) (1 shared connections)
- [Community 958](Community_958.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`

## Audit Trail

- EXTRACTED: 25 (96%)
- INFERRED: 1 (4%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*