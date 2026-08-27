# Community 554

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

- [Community 9](Community_9.md) (5 shared connections)
- [Community 418](Community_418.md) (3 shared connections)
- [Community 512](Community_512.md) (2 shared connections)
- [Community 150](Community_150.md) (2 shared connections)
- [Community 50](Community_50.md) (2 shared connections)
- [Community 178](Community_178.md) (1 shared connections)
- [Community 141](Community_141.md) (1 shared connections)
- [Community 419](Community_419.md) (1 shared connections)
- [Community 71](Community_71.md) (1 shared connections)
- [Community 57](Community_57.md) (1 shared connections)
- [Community 163](Community_163.md) (1 shared connections)

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