# Community 831

> 12 nodes · cohesion 0.20

## Key Concepts

- **EmailBackend** (8 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/filebased.py`
- **EmailBackend** (7 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/console.py`
- **.send_messages()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/console.py`
- **._get_filename()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/filebased.py`
- **.write_message()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/console.py`
- **.open()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/filebased.py`
- **ConsoleEmailBackend** (1 connections)
- **.__init__()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/console.py`
- **Write all messages to the stream in a thread-safe way.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/console.py`
- **.close()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/filebased.py`
- **.write_message()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/filebased.py`
- **Return a unique file name.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/filebased.py`

## Relationships

- [Community 117](Community_117.md) (3 shared connections)
- [Community 500](Community_500.md) (1 shared connections)
- [Community 101](Community_101.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/core/mail/backends/console.py`
- `raw/code/hyd-evaluation/django-django/django/core/mail/backends/filebased.py`

## Audit Trail

- EXTRACTED: 17 (94%)
- INFERRED: 1 (6%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*