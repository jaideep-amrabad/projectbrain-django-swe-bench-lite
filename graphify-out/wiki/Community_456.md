# Community 456

> 20 nodes · cohesion 0.12

## Key Concepts

- **RemoteUserBackend** (12 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **.authenticate()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **CustomRemoteUserBackend** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **.user_can_authenticate()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **AllowAllUsersRemoteUserBackend** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **.clean_username()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **.configure_user()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **RemoteUserNoCreateBackend** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **.authenticate()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **.get_user()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
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

- [Community 2](Community_2.md) (7 shared connections)
- [Community 323](Community_323.md) (3 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`

## Audit Trail

- EXTRACTED: 31 (97%)
- INFERRED: 1 (3%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*