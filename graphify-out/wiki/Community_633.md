# Community 633

> 16 nodes · cohesion 0.15

## Key Concepts

- **SessionStore** (12 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/sessions/backends/signed_cookies.py`
- **.save()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/sessions/backends/signed_cookies.py`
- **.create()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/sessions/backends/signed_cookies.py`
- **.cycle_key()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/sessions/backends/signed_cookies.py`
- **._get_session_key()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/sessions/backends/signed_cookies.py`
- **.load()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/sessions/backends/signed_cookies.py`
- **.delete()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/sessions/backends/signed_cookies.py`
- **.exists()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/sessions/backends/signed_cookies.py`
- **To create a new key, set the modified flag so that the cookie is set on the…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/sessions/backends/signed_cookies.py`
- **To save, get the session key as a securely signed string and then set the…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/sessions/backends/signed_cookies.py`
- **This method makes sense when you're talking to a shared resource, but it…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/sessions/backends/signed_cookies.py`
- **To delete, clear the session key and the underlying data structure and set the…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/sessions/backends/signed_cookies.py`
- **Keep the same data but with a new key. Call save() and it will automatically…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/sessions/backends/signed_cookies.py`
- **Instead of generating a random string, generate a secure url-safe…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/sessions/backends/signed_cookies.py`
- **Load the data from the key itself instead of fetching from some external data…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/sessions/backends/signed_cookies.py`
- **.clear_expired()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/sessions/backends/signed_cookies.py`

## Relationships

- [Community 1](Community_1.md) (2 shared connections)
- [Community 141](Community_141.md) (1 shared connections)
- [Community 844](Community_844.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/contrib/sessions/backends/signed_cookies.py`

## Audit Trail

- EXTRACTED: 21 (95%)
- INFERRED: 1 (5%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*