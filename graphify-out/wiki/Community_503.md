# Community 503

> 41 nodes · cohesion 0.06

## Key Concepts

- **BaseEmailBackend** (20 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/base.py`
- **EmailBackend** (11 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- **EmailBackend** (7 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/console.py`
- **EmailBackend** (5 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/locmem.py`
- **.close()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/base.py`
- **._send()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- **.send_messages()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- **custombackend.py** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/mail/custombackend.py`
- **EmailBackend** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/mail/custombackend.py`
- **.send_messages()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/console.py`
- **EmailBackend** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/dummy.py`
- **.close()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- **.open()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- **.__enter__()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/base.py`
- **.__exit__()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/base.py`
- **.open()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/base.py`
- **.send_messages()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/base.py`
- **.write_message()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/console.py`
- **.send_messages()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/locmem.py`
- **.connection_class()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- **.__init__()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/base.py`
- **Open a network connection. This method can be overwritten by backend…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/base.py`
- **Close a network connection.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/base.py`
- **Base class for email backend implementations. Subclasses must at least…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/base.py`
- **Send one or more EmailMessage objects and return the number of email messages…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/base.py`
- *... and 16 more nodes in this community*

## Relationships

- [Community 8](Community_8.md) (11 shared connections)
- [Community 1](Community_1.md) (3 shared connections)
- [Community 411](Community_411.md) (1 shared connections)
- [Community 2](Community_2.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/core/mail/backends/base.py`
- `raw/code/hyd-evaluation/django-django/django/core/mail/backends/console.py`
- `raw/code/hyd-evaluation/django-django/django/core/mail/backends/dummy.py`
- `raw/code/hyd-evaluation/django-django/django/core/mail/backends/locmem.py`
- `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- `raw/code/hyd-evaluation/django-django/tests/mail/custombackend.py`

## Audit Trail

- EXTRACTED: 61 (97%)
- INFERRED: 2 (3%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*