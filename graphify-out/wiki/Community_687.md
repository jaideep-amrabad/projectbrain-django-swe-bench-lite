# Community 687

> 12 nodes · cohesion 0.21

## Key Concepts

- **.end_blocking_transaction()** (6 connections) — `raw/code/hyd-evaluation/django-django/tests/select_for_update/tests.py`
- **.test_raw_lock_not_available()** (6 connections) — `raw/code/hyd-evaluation/django-django/tests/select_for_update/tests.py`
- **.start_blocking_transaction()** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/select_for_update/tests.py`
- **.test_block()** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/select_for_update/tests.py`
- **.test_nowait_raises_error_on_block()** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/select_for_update/tests.py`
- **.test_skip_locked_skips_locked_rows()** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/select_for_update/tests.py`
- **.raw()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/db/models/query.py`
- **.tearDown()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/select_for_update/tests.py`
- **If nowait is specified, we expect an error to be raised rather than blocking.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/select_for_update/tests.py`
- **If skip_locked is specified, the locked row is skipped resulting in…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/select_for_update/tests.py`
- **A thread running a select_for_update that accesses rows being touched by a…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/select_for_update/tests.py`
- **Running a raw query which can't obtain a FOR UPDATE lock raises the correct…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/select_for_update/tests.py`

## Relationships

- [Community 125](Community_125.md) (7 shared connections)
- [Community 31](Community_31.md) (4 shared connections)
- [Community 351](Community_351.md) (1 shared connections)
- [Community 45](Community_45.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/db/models/query.py`
- `raw/code/hyd-evaluation/django-django/tests/select_for_update/tests.py`

## Audit Trail

- EXTRACTED: 26 (96%)
- INFERRED: 1 (4%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*