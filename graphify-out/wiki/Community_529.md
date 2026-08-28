# Community 529

> 21 nodes · cohesion 0.13

## Key Concepts

- **get_token()** (20 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **csrf_tests/views.py** (17 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/views.py`
- **csrf()** (11 connections) — `raw/code/hyd-evaluation/django-django/django/template/context_processors.py`
- **_mask_cipher_secret()** (8 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **non_token_view_using_request_processor()** (8 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/views.py`
- **_get_new_csrf_string()** (7 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **.test_login_csrf_rotate()** (6 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_views.py`
- **csrf_token_error_handler()** (6 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/views.py`
- **_get_new_csrf_token()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **_sanitize_token()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **.test_csrf_validation_passes_after_process_request_login()** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **.test_process_response_get_token_not_used()** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **csrf_input()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/template/backends/utils.py`
- **Given a secret (assumed to be a string of CSRF_ALLOWED_CHARS), generate a token…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **Return the CSRF token required for a POST form. The token is an alphanumeric…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **Context processor that provides a CSRF token, or the string 'NOTPROVIDED' if it…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/template/context_processors.py`
- **CSRF check must access the CSRF token from the session or cookie, rather than…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **Makes sure that a login rotates the currently-used CSRF token.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_views.py`
- **If get_token() is not called, the view middleware does not add a cookie.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **Use the csrf view processor instead of the token.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/views.py`
- **This error handler accesses the CSRF token.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/views.py`

## Relationships

- [Community 10](Community_10.md) (13 shared connections)
- [Community 332](Community_332.md) (5 shared connections)
- [Community 271](Community_271.md) (5 shared connections)
- [Community 5](Community_5.md) (5 shared connections)
- [Community 620](Community_620.md) (4 shared connections)
- [Community 263](Community_263.md) (3 shared connections)
- [Community 669](Community_669.md) (3 shared connections)
- [Community 29](Community_29.md) (3 shared connections)
- [Community 4](Community_4.md) (2 shared connections)
- [Community 6](Community_6.md) (2 shared connections)
- [Community 57](Community_57.md) (2 shared connections)
- [Community 52](Community_52.md) (2 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- `raw/code/hyd-evaluation/django-django/django/template/backends/utils.py`
- `raw/code/hyd-evaluation/django-django/django/template/context_processors.py`
- `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_views.py`
- `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- `raw/code/hyd-evaluation/django-django/tests/csrf_tests/views.py`

## Audit Trail

- EXTRACTED: 84 (97%)
- INFERRED: 3 (3%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*