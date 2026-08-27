# Community 325

> 32 nodes · cohesion 0.09

## Key Concepts

- **MigrationExecutor** (50 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **sqlmigrate.py** (9 connections) — `raw/code/hyd-evaluation/django-django/django/core/management/commands/sqlmigrate.py`
- **.migrate()** (8 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **Command** (6 connections) — `raw/code/hyd-evaluation/django-django/django/core/management/commands/sqlmigrate.py`
- **.apply_migration()** (6 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **._create_project_state()** (6 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **.schema_editor()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/db/backends/base/base.py`
- **._migrate_all_backwards()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **.check_migrations()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/core/management/base.py`
- **._migrate_all_forwards()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **.migration_plan()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **.unapply_migration()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **.handle()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/management/commands/sqlmigrate.py`
- **.check_replacements()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **.collect_sql()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **.detect_soft_applied()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **.record_migration()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **Print a warning if the set of migrations on disk don't match the migrations in…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/management/base.py`
- **.add_arguments()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/management/commands/sqlmigrate.py`
- **.execute()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/management/commands/sqlmigrate.py`
- **Return a new instance of this backend's SchemaEditor.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/backends/base/base.py`
- **End-to-end migration execution - load migrations and run them up or down to a…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **Take a list of 2-tuples of the form (migration instance, False) and apply them…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **Take a list of 2-tuples of the form (migration instance, True) and unapply them…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **Take a migration plan and return a list of collected SQL statements that…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- *... and 7 more nodes in this community*

## Relationships

- [Community 22](Community_22.md) (21 shared connections)
- [Community 48](Community_48.md) (10 shared connections)
- [Community 49](Community_49.md) (8 shared connections)
- [Community 800](Community_800.md) (4 shared connections)
- [Community 217](Community_217.md) (2 shared connections)
- [Community 37](Community_37.md) (1 shared connections)
- [Community 0](Community_0.md) (1 shared connections)
- [Community 92](Community_92.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/core/management/base.py`
- `raw/code/hyd-evaluation/django-django/django/core/management/commands/sqlmigrate.py`
- `raw/code/hyd-evaluation/django-django/django/db/backends/base/base.py`
- `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`

## Audit Trail

- EXTRACTED: 82 (87%)
- INFERRED: 12 (13%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*