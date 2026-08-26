# Community 342

> 25 nodes · cohesion 0.10

## Key Concepts

- **ASGIHandler** (25 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.handle()** (10 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.create_request()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.send_response()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.test_read_body_thread()** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/asgi/tests.py`
- **.__call__()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.chunk_bytes()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.handle_uncaught_exception()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.listen_for_disconnect()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.read_body()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.run_get_response()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **.test_read_body_buffers_all_chunks()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/asgi/tests.py`
- **.test_read_body_multipart_not_limited()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/asgi/tests.py`
- **.test_read_body_no_limit()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/asgi/tests.py`
- **.__init__()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Handler for ASGI requests.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Async entrypoint - parses the request and hands off to get_response.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Handles the ASGI request. Called via the __call__ method.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Listen for disconnect from the client.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Reads an HTTP body from an ASGI connection.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Create the Request object and returns either (request, None) or (None,…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Last-chance handler for exceptions.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Encode and send a response out over ASGI.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Chunks some data up so it can be sent in reasonable size messages. Yields…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- **Write runs on correct thread depending on rollover.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/asgi/tests.py`

## Relationships

- [Community 939](Community_939.md) (4 shared connections)
- [Community 2](Community_2.md) (4 shared connections)
- [Community 881](Community_881.md) (4 shared connections)
- [Community 316](Community_316.md) (3 shared connections)
- [Community 5](Community_5.md) (2 shared connections)
- [Community 21](Community_21.md) (1 shared connections)
- [Community 481](Community_481.md) (1 shared connections)
- [Community 78](Community_78.md) (1 shared connections)
- [Community 15](Community_15.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/core/handlers/asgi.py`
- `raw/code/hyd-evaluation/django-django/tests/asgi/tests.py`

## Audit Trail

- EXTRACTED: 48 (92%)
- INFERRED: 4 (8%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*