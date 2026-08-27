# Community 605

> 22 nodes · cohesion 0.12

## Key Concepts

- **SessionStorage** (14 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`
- **FallbackStorage** (10 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/fallback.py`
- **MessageDecoder** (8 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/cookie.py`
- **fallback.py** (8 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/fallback.py`
- **storage/session.py** (8 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`
- **.process_messages()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/cookie.py`
- **._get()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`
- **.serialize_messages()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`
- **._store()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`
- **.decode()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/cookie.py`
- **._get()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/fallback.py`
- **._store()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/fallback.py`
- **.deserialize_messages()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`
- **Decode JSON that includes serialized ``Message`` instances.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/cookie.py`
- **.__init__()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/fallback.py`
- **Get a single list of messages from all storage backends.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/fallback.py`
- **Store the messages and return any unstored messages after trying all backends.…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/fallback.py`
- **Try to store all messages in the first backend. Store any unstored messages in…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/fallback.py`
- **Store messages in the session (that is, django.contrib.sessions).** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`
- **Retrieve a list of messages from the request's session. This storage always…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`
- **Store a list of messages to the request's session.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`
- **.__init__()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`

## Relationships

- [Community 505](Community_505.md) (7 shared connections)
- [Community 576](Community_576.md) (4 shared connections)
- [Community 486](Community_486.md) (4 shared connections)
- [Community 95](Community_95.md) (3 shared connections)
- [Community 604](Community_604.md) (2 shared connections)
- [Community 24](Community_24.md) (1 shared connections)
- [Community 336](Community_336.md) (1 shared connections)
- [Community 478](Community_478.md) (1 shared connections)
- [Community 977](Community_977.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/cookie.py`
- `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/fallback.py`
- `raw/code/hyd-evaluation/django-django/django/contrib/messages/storage/session.py`

## Audit Trail

- EXTRACTED: 44 (86%)
- INFERRED: 7 (14%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*