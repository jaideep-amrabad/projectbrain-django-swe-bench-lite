# Community 277

> 25 nodes · cohesion 0.13

## Key Concepts

- **middleware/csrf.py** (40 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **get_token()** (20 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **template/backends/utils.py** (10 connections) — `raw/code/hyd-evaluation/django-django/django/template/backends/utils.py`
- **is_same_domain()** (9 connections) — `raw/code/hyd-evaluation/django-django/django/utils/http.py`
- **_mask_cipher_secret()** (8 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **_compare_masked_tokens()** (7 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **_get_new_csrf_string()** (7 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **.test_login_csrf_rotate()** (6 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_views.py`
- **_get_new_csrf_token()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **rotate_token()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **_sanitize_token()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **.test_csrf_validation_passes_after_process_request_login()** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **_unmask_cipher_token()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **csrf_input()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/template/backends/utils.py`
- **IsSameDomainTests** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/utils_tests/test_http.py`
- **.test_bad()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/utils_tests/test_http.py`
- **.test_good()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/utils_tests/test_http.py`
- **Cross Site Request Forgery Middleware. This module provides a middleware that…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **Given a secret (assumed to be a string of CSRF_ALLOWED_CHARS), generate a token…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **Given a token (assumed to be a string of CSRF_ALLOWED_CHARS, of length…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **Return the CSRF token required for a POST form. The token is an alphanumeric…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **Change the CSRF token in use for a request - should be done on login for…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- **Return ``True`` if the host is either an exact match or a match to the wildcard…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/utils/http.py`
- **CSRF check must access the CSRF token from the session or cookie, rather than…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- **Makes sure that a login rotates the currently-used CSRF token.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_views.py`

## Relationships

- [Community 3](Community_3.md) (8 shared connections)
- [Community 584](Community_584.md) (8 shared connections)
- [Community 27](Community_27.md) (7 shared connections)
- [Community 1](Community_1.md) (7 shared connections)
- [Community 288](Community_288.md) (6 shared connections)
- [Community 2](Community_2.md) (4 shared connections)
- [Community 104](Community_104.md) (4 shared connections)
- [Community 93](Community_93.md) (4 shared connections)
- [Community 89](Community_89.md) (3 shared connections)
- [Community 70](Community_70.md) (3 shared connections)
- [Community 28](Community_28.md) (2 shared connections)
- [Community 170](Community_170.md) (2 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/middleware/csrf.py`
- `raw/code/hyd-evaluation/django-django/django/template/backends/utils.py`
- `raw/code/hyd-evaluation/django-django/django/utils/http.py`
- `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_remote_user.py`
- `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_views.py`
- `raw/code/hyd-evaluation/django-django/tests/utils_tests/test_http.py`

## Audit Trail

- EXTRACTED: 111 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*