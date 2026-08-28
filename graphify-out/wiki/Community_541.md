# Community 541

> 25 nodes · cohesion 0.11

## Key Concepts

- **token_view()** (24 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/views.py`
- **._check_token_present()** (10 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **._get_csrf_cookie_request()** (8 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **.test_token_node_empty_csrf_cookie()** (8 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **.test_get_token_for_exempt_view()** (7 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **.test_token_node_no_csrf_cookie()** (7 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **.test_token_node_with_new_csrf_cookie()** (7 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **.test_bare_secret_accepted_and_not_replaced()** (7 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **.test_masked_secret_accepted_and_replaced()** (7 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **.test_cookie_not_reset_on_accepted_request()** (6 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **.test_get_token_for_requires_csrf_token_view()** (6 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **.test_token_node_with_csrf_cookie()** (6 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **.test_https_malformed_host()** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **.test_put_and_delete_allowed()** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **CsrfTokenNode works when no CSRF cookie is set.** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **For a view that uses the csrf_token, the csrf cookie is replaced with the…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **The csrf cookie is left unchanged if originally not masked.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **The method argument defaults to "GET". The cookie argument defaults to this…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **HTTP PUT and DELETE can get through with X-CSRFToken and a cookie.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **A new token is sent if the csrf_cookie is the empty string.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **get_token still works for a view decorated with 'csrf_exempt'.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **get_token() works for a view decorated solely with requires_csrf_token.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **CsrfTokenNode works when a CSRF cookie is created by the middleware (when one…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **The csrf token used in posts is changed on every request (although stays…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- **CsrfViewMiddleware generates a 403 response if it receives an HTTPS request…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`

## Relationships

- [Community 37](Community_37.md) (16 shared connections)
- [Community 446](Community_446.md) (16 shared connections)
- [Community 548](Community_548.md) (9 shared connections)
- [Community 40](Community_40.md) (8 shared connections)
- [Community 693](Community_693.md) (3 shared connections)
- [Community 15](Community_15.md) (3 shared connections)
- [Community 0](Community_0.md) (1 shared connections)
- [Community 167](Community_167.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/tests/csrf_tests/tests.py`
- `raw/code/hyd-evaluation/django-django/tests/csrf_tests/views.py`

## Audit Trail

- EXTRACTED: 71 (78%)
- INFERRED: 20 (22%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*