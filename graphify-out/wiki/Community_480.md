# Community 480

> 24 nodes · cohesion 0.12

## Key Concepts

- **ASGIHandler** (19 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **ASGIStaticFilesHandler** (13 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/staticfiles/handlers.py`
- **.handle()** (8 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **TestASGIStaticFilesHandler** (6 connections) — `raw/code/hyd-evaluation/django-django/tests/staticfiles_tests/test_handlers.py`
- **.create_request()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.send_response()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.read_body()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.__call__()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.chunk_bytes()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.get_script_prefix()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.handle_uncaught_exception()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.test_get_async_response()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/staticfiles_tests/test_handlers.py`
- **.test_get_async_response_not_found()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/staticfiles_tests/test_handlers.py`
- **ASGI application which wraps another and intercepts requests for static files,…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/staticfiles/handlers.py`
- **.__init__()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Handler for ASGI requests.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Async entrypoint - parses the request and hands off to get_response.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Handles the ASGI request. Called via the __call__ method.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Reads an HTTP body from an ASGI connection.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Create the Request object and returns either (request, None) or (None,…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Last-chance handler for exceptions.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Encode and send a response out over ASGI.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Chunks some data up so it can be sent in reasonable size messages. Yields…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Return the script prefix to use from either the scope or a setting.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`

## Relationships

- [Community 5](Community_5.md) (6 shared connections)
- [Community 2](Community_2.md) (5 shared connections)
- [Community 625](Community_625.md) (3 shared connections)
- [Community 523](Community_523.md) (3 shared connections)
- [Community 44](Community_44.md) (1 shared connections)
- [Community 9](Community_9.md) (1 shared connections)
- [Community 97](Community_97.md) (1 shared connections)
- [Community 132](Community_132.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/contrib/staticfiles/handlers.py`
- `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- `raw/code/hyd-evaluation/django-django/tests/staticfiles_tests/test_handlers.py`

## Audit Trail

- EXTRACTED: 51 (93%)
- INFERRED: 4 (7%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*