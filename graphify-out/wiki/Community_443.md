# Community 443

> 20 nodes · cohesion 0.12

## Key Concepts

- **SessionStorage** (14 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`
- **FallbackStorage** (10 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/fallback.py`
- **MessageDecoder** (8 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/cookie.py`
- **.process_messages()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/cookie.py`
- **._get()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`
- **.serialize_messages()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`
- **._store()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`
- **.decode()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/cookie.py`
- **._get()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/fallback.py`
- **._store()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/fallback.py`
- **.deserialize_messages()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`
- **.__init__()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`
- **Decode JSON that includes serialized ``Message`` instances.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/cookie.py`
- **.__init__()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/fallback.py`
- **Get a single list of messages from all storage backends.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/fallback.py`
- **Store the messages and return any unstored messages after trying all backends.…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/fallback.py`
- **Try to store all messages in the first backend. Store any unstored messages in…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/fallback.py`
- **Retrieve a list of messages from the request's session. This storage always…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`
- **Store a list of messages to the request's session.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`
- **Store messages in the session (that is, django.contrib.sessions).** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`

## Relationships

- [Community 304](Community_304.md) (10 shared connections)
- [Community 476](Community_476.md) (2 shared connections)
- [Community 712](Community_712.md) (1 shared connections)
- [Community 49](Community_49.md) (1 shared connections)
- [Community 510](Community_510.md) (1 shared connections)
- [Community 490](Community_490.md) (1 shared connections)
- [Community 485](Community_485.md) (1 shared connections)
- [Community 1001](Community_1001.md) (1 shared connections)
- [Community 13](Community_13.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/cookie.py`
- `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/fallback.py`
- `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`

## Audit Trail

- EXTRACTED: 34 (83%)
- INFERRED: 7 (17%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*