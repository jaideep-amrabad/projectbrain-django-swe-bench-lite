# Community 308

> 32 nodes · cohesion 0.07

## Key Concepts

- **MigrationRecorder** (50 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/recorder.py`
- **.ensure_schema()** (6 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/recorder.py`
- **.test_migrate_inconsistent_history()** (6 connections) — `raw/code/hyd-evaluation/django-django/tests/migrations/test_commands.py`
- **.test_migrate_record_replaced()** (6 connections) — `raw/code/hyd-evaluation/django-django/tests/migrations/test_commands.py`
- **.test_migrate_record_squashed()** (6 connections) — `raw/code/hyd-evaluation/django-django/tests/migrations/test_commands.py`
- **.test_showmigrations_list()** (6 connections) — `raw/code/hyd-evaluation/django-django/tests/migrations/test_commands.py`
- **.test_makemigrations_inconsistent_history()** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/migrations/test_commands.py`
- **RecorderTests** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/migrations/test_loader.py`
- **.check_consistent_history()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/loader.py`
- **.has_table()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/recorder.py`
- **.test_apply()** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/migrations/test_loader.py`
- **.__init__()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **.applied_migrations()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/recorder.py`
- **.record_applied()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/recorder.py`
- **.record_unapplied()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/recorder.py`
- **.flush()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/recorder.py`
- **Record that a migration was applied.** (2 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/recorder.py`
- **Raise InconsistentMigrationHistory if any applied migrations have unapplied…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/loader.py`
- **.__init__()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/recorder.py`
- **.migration_qs()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/recorder.py`
- **Deal with storing migration records in the database. Because this table is…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/recorder.py`
- **Return True if the django_migrations table exists.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/recorder.py`
- **Ensure the table exists and has the correct schema.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/recorder.py`
- **Return a dict mapping (app_name, migration_name) to Migration instances for all…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/recorder.py`
- **Delete all migration records. Useful for testing migrations.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/recorder.py`
- *... and 7 more nodes in this community*

## Relationships

- [Community 177](Community_177.md) (18 shared connections)
- [Community 79](Community_79.md) (13 shared connections)
- [Community 210](Community_210.md) (9 shared connections)
- [Community 19](Community_19.md) (6 shared connections)
- [Community 9](Community_9.md) (4 shared connections)
- [Community 506](Community_506.md) (2 shared connections)
- [Community 322](Community_322.md) (2 shared connections)
- [Community 282](Community_282.md) (1 shared connections)
- [Community 0](Community_0.md) (1 shared connections)
- [Community 353](Community_353.md) (1 shared connections)
- [Community 60](Community_60.md) (1 shared connections)
- [Community 5](Community_5.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- `raw/code/hyd-evaluation/django-django/django/db/migrations/loader.py`
- `raw/code/hyd-evaluation/django-django/django/db/migrations/recorder.py`
- `raw/code/hyd-evaluation/django-django/tests/migrations/test_commands.py`
- `raw/code/hyd-evaluation/django-django/tests/migrations/test_loader.py`

## Audit Trail

- EXTRACTED: 78 (81%)
- INFERRED: 18 (19%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*