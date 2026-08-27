# Community 417

> 24 nodes · cohesion 0.11

## Key Concepts

- **MigrationRecorder** (50 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/recorder.py`
- **.ensure_schema()** (6 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/recorder.py`
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
- **makemigrations should raise InconsistentMigrationHistory exception if there are…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/migrations/test_commands.py`
- **Tests recording migrations as applied or not.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/migrations/test_loader.py`
- **Tests marking migrations as applied/unapplied.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/migrations/test_loader.py`

## Relationships

- [Community 91](Community_91.md) (15 shared connections)
- [Community 158](Community_158.md) (14 shared connections)
- [Community 11](Community_11.md) (8 shared connections)
- [Community 529](Community_529.md) (2 shared connections)
- [Community 71](Community_71.md) (2 shared connections)
- [Community 398](Community_398.md) (2 shared connections)
- [Community 217](Community_217.md) (1 shared connections)
- [Community 3](Community_3.md) (1 shared connections)
- [Community 526](Community_526.md) (1 shared connections)
- [Community 602](Community_602.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- `raw/code/hyd-evaluation/django-django/django/db/migrations/loader.py`
- `raw/code/hyd-evaluation/django-django/django/db/migrations/recorder.py`
- `raw/code/hyd-evaluation/django-django/tests/migrations/test_commands.py`
- `raw/code/hyd-evaluation/django-django/tests/migrations/test_loader.py`

## Audit Trail

- EXTRACTED: 62 (82%)
- INFERRED: 14 (18%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*