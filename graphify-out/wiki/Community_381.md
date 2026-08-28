# Community 381

> 30 nodes · cohesion 0.10

## Key Concepts

- **ASGIHandler** (22 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **ASGIStaticFilesHandler** (15 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/staticfiles/handlers.py`
- **.handle()** (10 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **TestASGIStaticFilesHandler** (7 connections) — `raw/code/hyd-evaluation/django-django/tests/staticfiles_tests/test_handlers.py`
- **.create_request()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.send_response()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.listen_for_disconnect()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.read_body()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **MockApplication** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/staticfiles_tests/test_handlers.py`
- **.__call__()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.chunk_bytes()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.handle_uncaught_exception()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.test_get_async_response()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/staticfiles_tests/test_handlers.py`
- **.test_get_async_response_not_found()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/staticfiles_tests/test_handlers.py`
- **.test_non_http_requests_passed_to_the_wrapped_application()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/staticfiles_tests/test_handlers.py`
- **.run_get_response()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.get_response_async()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/staticfiles/handlers.py`
- **ASGI application which wraps another and intercepts requests for static files,…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/staticfiles/handlers.py`
- **.__init__()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Handler for ASGI requests.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Async entrypoint - parses the request and hands off to get_response.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Handles the ASGI request. Called via the __call__ method.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Listen for disconnect from the client.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Reads an HTTP body from an ASGI connection.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Create the Request object and returns either (request, None) or (None,…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- *... and 5 more nodes in this community*

## Relationships

- [Community 1](Community_1.md) (16 shared connections)
- [Community 331](Community_331.md) (4 shared connections)
- [Community 464](Community_464.md) (3 shared connections)
- [Community 22](Community_22.md) (1 shared connections)
- [Community 587](Community_587.md) (1 shared connections)
- [Community 1103](Community_1103.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/contrib/staticfiles/handlers.py`
- `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- `raw/code/hyd-evaluation/django-django/tests/staticfiles_tests/test_handlers.py`

## Audit Trail

- EXTRACTED: 63 (93%)
- INFERRED: 5 (7%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*