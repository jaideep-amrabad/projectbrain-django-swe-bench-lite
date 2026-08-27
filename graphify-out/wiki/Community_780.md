# Community 780

> 12 nodes · cohesion 0.17

## Key Concepts

- **AuthRouter** (11 connections) — `raw/code/hyd-evaluation/django-django/tests/multiple_database/routers.py`
- **.test_migrate_selection()** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/multiple_database/tests.py`
- **.allow_migrate()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/multiple_database/routers.py`
- **.allow_relation()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/multiple_database/routers.py`
- **.db_for_read()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/multiple_database/routers.py`
- **.db_for_write()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/multiple_database/routers.py`
- **Control all database operations on models in the contrib.auth application.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/multiple_database/routers.py`
- **Point all read operations on auth models to 'default** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/multiple_database/routers.py`
- **Point all operations on auth models to 'other** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/multiple_database/routers.py`
- **Allow any relation if a model in Auth is involved** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/multiple_database/routers.py`
- **Make sure the auth app only appears on the 'other' db** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/multiple_database/routers.py`
- **Synchronization behavior is predictable** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/multiple_database/tests.py`

## Relationships

- [Community 440](Community_440.md) (3 shared connections)
- [Community 571](Community_571.md) (2 shared connections)
- [Community 15](Community_15.md) (1 shared connections)
- [Community 239](Community_239.md) (1 shared connections)
- [Community 3](Community_3.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/tests/multiple_database/routers.py`
- `raw/code/hyd-evaluation/django-django/tests/multiple_database/tests.py`

## Audit Trail

- EXTRACTED: 17 (89%)
- INFERRED: 2 (11%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*