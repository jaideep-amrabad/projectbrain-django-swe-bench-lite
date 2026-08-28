# Community 504

> 22 nodes · cohesion 0.10

## Key Concepts

- **RemoteUserBackend** (13 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **.authenticate()** (6 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **CustomRemoteUserBackend** (6 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **.user_can_authenticate()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **AllowAllUsersRemoteUserBackend** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **.clean_username()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **.configure_user()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **CustomRemoteUserNoCreatedArgumentBackend** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **RemoteUserNoCreateBackend** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **.authenticate()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **.get_user()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **.clean_username()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **.configure_user()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **This backend is to be used in conjunction with the ``RemoteUserMiddleware``…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **The username passed as ``remote_user`` is considered trusted. Return the…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **Perform any cleaning on the "username" prior to using it to get or create the…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **Configure a user and return the updated user. By default, return the user…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- **.configure_user()** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **Backend that doesn't create unknown users.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **Backend that overrides RemoteUserBackend methods.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **Grabs username before the @ character.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **Sets user's email address using the email specified in an HTTP header. Sets…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`

## Relationships

- [Community 2](Community_2.md) (5 shared connections)
- [Community 281](Community_281.md) (3 shared connections)
- [Community 7](Community_7.md) (2 shared connections)
- [Community 1](Community_1.md) (1 shared connections)
- [Community 808](Community_808.md) (1 shared connections)
- [Community 19](Community_19.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/contrib/auth/backends.py`
- `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`

## Audit Trail

- EXTRACTED: 35 (95%)
- INFERRED: 2 (5%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*