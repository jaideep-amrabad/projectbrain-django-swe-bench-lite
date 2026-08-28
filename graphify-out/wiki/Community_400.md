# Community 400

> 24 nodes · cohesion 0.14

## Key Concepts

- **SessionMiddleware** (21 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/sessions/middleware.py`
- **.middleware()** (19 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/test_security.py`
- **SessionMiddlewareTests** (14 connections) — `raw/code/hyd-evaluation/django-django/tests/sessions_tests/tests.py`
- **.test_login_csrf_rotate()** (6 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_views.py`
- **.test_empty_session_saved()** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/sessions_tests/tests.py`
- **.test_httponly_session_cookie()** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/sessions_tests/tests.py`
- **.test_no_httponly_session_cookie()** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/sessions_tests/tests.py`
- **.test_samesite_session_cookie()** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/sessions_tests/tests.py`
- **.test_secure_session_cookie()** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/sessions_tests/tests.py`
- **.test_session_delete_on_end_with_custom_domain_and_path()** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/sessions_tests/tests.py`
- **.test_flush_empty_without_session_cookie_doesnt_set_cookie()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/sessions_tests/tests.py`
- **.test_session_delete_on_end()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/sessions_tests/tests.py`
- **.test_session_update_error_redirect()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/sessions_tests/tests.py`
- **.__init__()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/sessions/middleware.py`
- **SessionMiddlewareSubclass** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/admin_checks/tests.py`
- **.test_coroutine()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/deprecation/test_middleware_mixin.py`
- **.test_passing_explicit_none()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/deprecation/test_middleware_mixin.py`
- **.response()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/test_security.py`
- **.get_response_touching_session()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/sessions_tests/tests.py`
- **.test_session_save_on_500()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/sessions_tests/tests.py`
- **custom_urlconf_middleware()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/template_tests/test_response.py`
- **.process_request()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/sessions/middleware.py`
- **Makes sure that a login rotates the currently-used CSRF token.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_views.py`
- **If a session is emptied of data but still has a key, it should still be updated.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/sessions_tests/tests.py`

## Relationships

- [Community 70](Community_70.md) (7 shared connections)
- [Community 5](Community_5.md) (5 shared connections)
- [Community 224](Community_224.md) (4 shared connections)
- [Community 38](Community_38.md) (2 shared connections)
- [Community 18](Community_18.md) (2 shared connections)
- [Community 10](Community_10.md) (2 shared connections)
- [Community 12](Community_12.md) (2 shared connections)
- [Community 386](Community_386.md) (1 shared connections)
- [Community 58](Community_58.md) (1 shared connections)
- [Community 63](Community_63.md) (1 shared connections)
- [Community 187](Community_187.md) (1 shared connections)
- [Community 531](Community_531.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/contrib/sessions/middleware.py`
- `raw/code/hyd-evaluation/django-django/tests/admin_checks/tests.py`
- `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_views.py`
- `raw/code/hyd-evaluation/django-django/tests/deprecation/test_middleware_mixin.py`
- `raw/code/hyd-evaluation/django-django/tests/middleware/test_security.py`
- `raw/code/hyd-evaluation/django-django/tests/sessions_tests/tests.py`
- `raw/code/hyd-evaluation/django-django/tests/template_tests/test_response.py`

## Audit Trail

- EXTRACTED: 57 (78%)
- INFERRED: 16 (22%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*