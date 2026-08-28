# Community 833

> 11 nodes · cohesion 0.20

## Key Concepts

- **QuotaUploadHandler** (10 connections) — `raw/code/hyd-evaluation/django-django/tests/file_uploads/uploadhandler.py`
- **file_upload_echo()** (6 connections) — `raw/code/hyd-evaluation/django-django/tests/file_uploads/views.py`
- **file_upload_quota()** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/file_uploads/views.py`
- **file_upload_quota_broken()** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/file_uploads/views.py`
- **file_upload_errors()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/file_uploads/views.py`
- **.receive_data_chunk()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/file_uploads/uploadhandler.py`
- **.file_complete()** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/file_uploads/uploadhandler.py`
- **This test upload handler terminates the connection if more than a quota (5MB)…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/file_uploads/uploadhandler.py`
- **You can't change handlers after reading FILES; this view shouldn't work.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/file_uploads/views.py`
- **Simple view to echo back info about uploaded files for tests.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/file_uploads/views.py`
- **Dynamically add in an upload handler.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/file_uploads/views.py`

## Relationships

- [Community 461](Community_461.md) (5 shared connections)
- [Community 769](Community_769.md) (3 shared connections)
- [Community 622](Community_622.md) (1 shared connections)
- [Community 841](Community_841.md) (1 shared connections)
- [Community 11](Community_11.md) (1 shared connections)
- [Community 875](Community_875.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/tests/file_uploads/uploadhandler.py`
- `raw/code/hyd-evaluation/django-django/tests/file_uploads/views.py`

## Audit Trail

- EXTRACTED: 22 (96%)
- INFERRED: 1 (4%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*