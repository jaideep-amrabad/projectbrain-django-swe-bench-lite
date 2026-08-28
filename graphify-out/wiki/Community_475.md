# Community 475

> 24 nodes · cohesion 0.12

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
- **_non_atomic_requests()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/db/transaction.py`
- **.test_sync_to_async_uses_base_thread_and_connection()** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/deprecation/test_middleware_mixin.py`
- **.process_exception_by_middleware()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **reset_urlconf()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **not_in_transaction()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/handlers/views.py`
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

- [Community 2](Community_2.md) (6 shared connections)
- [Community 26](Community_26.md) (3 shared connections)
- [Community 772](Community_772.md) (2 shared connections)
- [Community 996](Community_996.md) (2 shared connections)
- [Community 207](Community_207.md) (2 shared connections)
- [Community 106](Community_106.md) (2 shared connections)
- [Community 778](Community_778.md) (1 shared connections)
- [Community 395](Community_395.md) (1 shared connections)
- [Community 9](Community_9.md) (1 shared connections)
- [Community 196](Community_196.md) (1 shared connections)
- [Community 56](Community_56.md) (1 shared connections)
- [Community 63](Community_63.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- `raw/code/hyd-evaluation/django-django/django/db/transaction.py`
- `raw/code/hyd-evaluation/django-django/django/urls/base.py`
- `raw/code/hyd-evaluation/django-django/tests/deprecation/test_middleware_mixin.py`
- `raw/code/hyd-evaluation/django-django/tests/handlers/views.py`

## Audit Trail

- EXTRACTED: 50 (85%)
- INFERRED: 9 (15%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*