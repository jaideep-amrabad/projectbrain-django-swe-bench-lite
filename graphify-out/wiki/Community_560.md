# Community 560

> 19 nodes · cohesion 0.16

## Key Concepts

- **BaseHandler** (12 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **.get_response()** (10 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **.get_response_async()** (9 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **.load_middleware()** (7 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **.resolve_request()** (6 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **.check_response()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **.make_view_atomic()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **_non_atomic_requests()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/db/transaction.py`
- **.adapt_method_mode()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **.process_exception_by_middleware()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **not_in_transaction()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/handlers/views.py`
- **Resolve and call the view, then apply view, exception, and template_response…** (2 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **Adapt a method to be in the correct "mode": - If is_async is False: -…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **Return an HttpResponse object for the given HttpRequest.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **Asynchronous version of get_response. Funneling everything, including WSGI,…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **Populate middleware lists from settings.MIDDLEWARE. Must be called after the…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **Retrieve/set the urlconf for the request. Return the view resolved, with its…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **Raise an error if the view returned None or an uncalled coroutine.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- **Pass the exception to the exception middleware. If no middleware return a…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`

## Relationships

- [Community 9](Community_9.md) (6 shared connections)
- [Community 391](Community_391.md) (3 shared connections)
- [Community 423](Community_423.md) (2 shared connections)
- [Community 108](Community_108.md) (2 shared connections)
- [Community 2](Community_2.md) (2 shared connections)
- [Community 24](Community_24.md) (1 shared connections)
- [Community 152](Community_152.md) (1 shared connections)
- [Community 13](Community_13.md) (1 shared connections)
- [Community 273](Community_273.md) (1 shared connections)
- [Community 218](Community_218.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/core/handlers/base.py`
- `raw/code/hyd-evaluation/django-django/django/db/transaction.py`
- `raw/code/hyd-evaluation/django-django/tests/handlers/views.py`

## Audit Trail

- EXTRACTED: 41 (87%)
- INFERRED: 6 (13%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*