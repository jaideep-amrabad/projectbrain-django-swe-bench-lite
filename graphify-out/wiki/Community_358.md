# Community 358

> 31 nodes · cohesion 0.08

## Key Concepts

- **RemoteUserBackend** (12 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **RemoteUserMiddleware** (10 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/middleware.py`
- **.authenticate()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **CustomRemoteUserBackend** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **.user_can_authenticate()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **.process_request()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/middleware.py`
- **._remove_invalid_user()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/middleware.py`
- **AllowAllUsersRemoteUserBackend** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **.clean_username()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **.configure_user()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **PersistentRemoteUserMiddleware** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/middleware.py`
- **.clean_username()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/middleware.py`
- **CustomHeaderMiddleware** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **RemoteUserNoCreateBackend** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **.authenticate()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **.get_user()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **.clean_username()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **.configure_user()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **This backend is to be used in conjunction with the ``RemoteUserMiddleware``…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **The username passed as ``remote_user`` is considered trusted. Return the…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **Perform any cleaning on the "username" prior to using it to get or create the…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **Configure a user after creation and return the updated user. By default, return…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **Middleware for Web-server provided authentication on logon pages. Like…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/middleware.py`
- **Middleware for utilizing Web-server-provided authentication. If request.user is…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/middleware.py`
- **Allow the backend to clean the username, if the backend defines a…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/middleware.py`
- *... and 6 more nodes in this community*

## Relationships

- [Community 4](Community_4.md) (7 shared connections)
- [Community 35](Community_35.md) (5 shared connections)
- [Community 123](Community_123.md) (3 shared connections)
- [Community 416](Community_416.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- `raw/code/hyd-evaluation/django-django/django/contrib/auth/middleware.py`
- `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`

## Audit Trail

- EXTRACTED: 50 (98%)
- INFERRED: 1 (2%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*