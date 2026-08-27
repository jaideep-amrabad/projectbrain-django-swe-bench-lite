# Community 374

> 30 nodes · cohesion 0.10

## Key Concepts

- **MigrationExecutor** (50 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **sqlmigrate.py** (9 connections) — `raw/code/hyd-evaluation/django-django/django/core/management/commands/sqlmigrate.py`
- **.migrate()** (8 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **Command** (6 connections) — `raw/code/hyd-evaluation/django-django/django/core/management/commands/sqlmigrate.py`
- **.apply_migration()** (6 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **._create_project_state()** (6 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **.schema_editor()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/db/backends/base/base.py`
- **._migrate_all_backwards()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **._migrate_all_forwards()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **.migration_plan()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **.unapply_migration()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **.handle()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/core/management/commands/sqlmigrate.py`
- **.check_replacements()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **.collect_sql()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **.detect_soft_applied()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **.record_migration()** (2 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **.add_arguments()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/management/commands/sqlmigrate.py`
- **.execute()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/core/management/commands/sqlmigrate.py`
- **Return a new instance of this backend's SchemaEditor.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/backends/base/base.py`
- **End-to-end migration execution - load migrations and run them up or down to a…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **Take a list of 2-tuples of the form (migration instance, False) and apply them…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **Take a list of 2-tuples of the form (migration instance, True) and unapply them…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **Take a migration plan and return a list of collected SQL statements that…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **Given a set of targets, return a list of (Migration instance, backwards?).** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- **Run a migration forwards.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`
- *... and 5 more nodes in this community*

## Relationships

- [Community 22](Community_22.md) (21 shared connections)
- [Community 48](Community_48.md) (10 shared connections)
- [Community 57](Community_57.md) (7 shared connections)
- [Community 158](Community_158.md) (3 shared connections)
- [Community 216](Community_216.md) (2 shared connections)
- [Community 33](Community_33.md) (1 shared connections)
- [Community 5](Community_5.md) (1 shared connections)
- [Community 93](Community_93.md) (1 shared connections)
- [Community 360](Community_360.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/core/management/commands/sqlmigrate.py`
- `raw/code/hyd-evaluation/django-django/django/db/backends/base/base.py`
- `raw/code/hyd-evaluation/django-django/django/db/migrations/executor.py`

## Audit Trail

- EXTRACTED: 79 (87%)
- INFERRED: 12 (13%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*