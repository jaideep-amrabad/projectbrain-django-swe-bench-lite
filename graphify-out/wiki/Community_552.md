# Community 552

> 19 nodes · cohesion 0.12

## Key Concepts

- **sanitize_address()** (12 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/message.py`
- **EmailBackend** (9 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- **._send()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- **.send_messages()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- **.close()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- **.open()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- **.test_sanitize_address()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/mail/tests.py`
- **.connection_class()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- **ValueError** (2 connections)
- **.test_sanitize_address_header_injection()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/mail/tests.py`
- **.test_sanitize_address_invalid()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/mail/tests.py`
- **.__init__()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- **A helper method that does the actual sending.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- **A wrapper that manages the SMTP network connection.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- **Ensure an open connection to the email server. Return whether or not a new…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- **Close the connection to the email server.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- **Send one or more EmailMessage objects and return the number of email messages…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- **Format a pair of (name, address) or an email address string.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/mail/message.py`
- **Email addresses are properly sanitized.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/mail/tests.py`

## Relationships

- [Community 604](Community_604.md) (5 shared connections)
- [Community 128](Community_128.md) (3 shared connections)
- [Community 384](Community_384.md) (1 shared connections)
- [Community 1](Community_1.md) (1 shared connections)
- [Community 30](Community_30.md) (1 shared connections)
- [Community 424](Community_424.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/core/mail/backends/smtp.py`
- `raw/code/hyd-evaluation/django-django/django/core/mail/message.py`
- `raw/code/hyd-evaluation/django-django/tests/mail/tests.py`

## Audit Trail

- EXTRACTED: 33 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*