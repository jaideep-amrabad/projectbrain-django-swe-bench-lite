# Community 595

> 27 nodes · cohesion 0.09

## Key Concepts

- **RemoteUserBackend** (12 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **RemoteUserMiddleware** (11 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/middleware.py`
- **.authenticate()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **CustomRemoteUserBackend** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **.process_request()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/middleware.py`
- **._remove_invalid_user()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/middleware.py`
- **.clean_username()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **.configure_user()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **PersistentRemoteUserMiddleware** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/middleware.py`
- **.clean_username()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/middleware.py`
- **CustomHeaderMiddleware** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **RemoteUserNoCreateBackend** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **.clean_username()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **.configure_user()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **This backend is to be used in conjunction with the ``RemoteUserMiddleware``…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **The username passed as ``remote_user`` is considered trusted. Return the…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **Perform any cleaning on the "username" prior to using it to get or create the…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **Configure a user after creation and return the updated user. By default, return…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **Middleware for Web-server provided authentication on logon pages. Like…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/middleware.py`
- **Middleware for utilizing Web-server-provided authentication. If request.user is…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/middleware.py`
- **Allow the backend to clean the username, if the backend defines a…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/middleware.py`
- **Remove the current authenticated user in the request which is invalid but only…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/middleware.py`
- **Backend that doesn't create unknown users.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **Backend that overrides RemoteUserBackend methods.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **Grabs username before the @ character.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- *... and 2 more nodes in this community*

## Relationships

- [Community 4](Community_4.md) (8 shared connections)
- [Community 10](Community_10.md) (5 shared connections)
- [Community 231](Community_231.md) (3 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- `raw/code/hyd-evaluation/django-django/django/contrib/auth/middleware.py`
- `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`

## Audit Trail

- EXTRACTED: 45 (98%)
- INFERRED: 1 (2%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*