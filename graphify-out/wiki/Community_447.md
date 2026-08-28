# Community 447

> 22 nodes · cohesion 0.14

## Key Concepts

- **BaseHandler** (12 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **.get_response()** (11 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **set_urlconf()** (10 connections) — `raw/code/hyd-evaluation/django-django/django/urls/base.py`
- **.get_response_async()** (9 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **.resolve_request()** (6 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **async_to_sync** (5 connections)
- **.adapt_method_mode()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **.check_response()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **.make_view_atomic()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **.test_sync_to_async_uses_base_thread_and_connection()** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/deprecation/test_middleware_mixin.py`
- **.process_exception_by_middleware()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **reset_urlconf()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **Resolve and call the view, then apply view, exception, and template_response…** (2 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **Adapt a method to be in the correct "mode": - If is_async is False: -…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **Return an HttpResponse object for the given HttpRequest.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **Asynchronous version of get_response. Funneling everything, including WSGI,…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **Retrieve/set the urlconf for the request. Return the view resolved, with its…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **Raise an error if the view returned None or an uncalled coroutine.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **Pass the exception to the exception middleware. If no middleware return a…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **Reset the URLconf after each request is finished.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **Set the URLconf for the current thread (overriding the default one in…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/urls/base.py`
- **The process_request() and process_response() hooks must be called with the…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/deprecation/test_middleware_mixin.py`

## Relationships

- [Community 12](Community_12.md) (8 shared connections)
- [Community 14](Community_14.md) (3 shared connections)
- [Community 747](Community_747.md) (2 shared connections)
- [Community 91](Community_91.md) (2 shared connections)
- [Community 294](Community_294.md) (2 shared connections)
- [Community 579](Community_579.md) (1 shared connections)
- [Community 936](Community_936.md) (1 shared connections)
- [Community 7](Community_7.md) (1 shared connections)
- [Community 50](Community_50.md) (1 shared connections)
- [Community 131](Community_131.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- `raw/code/hyd-evaluation/django-django/django/urls/base.py`
- `raw/code/hyd-evaluation/django-django/tests/deprecation/test_middleware_mixin.py`

## Audit Trail

- EXTRACTED: 46 (85%)
- INFERRED: 8 (15%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*