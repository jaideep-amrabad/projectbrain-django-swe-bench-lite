# Community 495

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

- [Community 107](Community_107.md) (13 shared connections)
- [Community 193](Community_193.md) (9 shared connections)
- [Community 8](Community_8.md) (9 shared connections)
- [Community 95](Community_95.md) (6 shared connections)
- [Community 579](Community_579.md) (2 shared connections)
- [Community 460](Community_460.md) (2 shared connections)
- [Community 783](Community_783.md) (1 shared connections)
- [Community 176](Community_176.md) (1 shared connections)
- [Community 120](Community_120.md) (1 shared connections)
- [Community 0](Community_0.md) (1 shared connections)
- [Community 73](Community_73.md) (1 shared connections)
- [Community 30](Community_30.md) (1 shared connections)

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