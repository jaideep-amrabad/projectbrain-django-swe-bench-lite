# TestCase

> God node · 1142 connections · `raw/code/hyd-evaluation/django-django/django/test/testcases.py`

**Community:** [Community 15](Community_15.md)

## Connections by Relation

### calls
- .test_handle_add_error_during_test() `INFERRED`
- .test_handle_add_failure() `INFERRED`
- .test_handle_add_success() `INFERRED`

### contains
- testcases.py `EXTRACTED`

### imports
- django/test/__init__.py `EXTRACTED`
- queries/tests.py `EXTRACTED`
- model_forms/tests.py `EXTRACTED`
- cache/tests.py `EXTRACTED`
- admin_scripts/tests.py `EXTRACTED`
- admin_changelist/tests.py `EXTRACTED`
- expressions/tests.py `EXTRACTED`
- test_utils/tests.py `EXTRACTED`
- i18n/tests.py `EXTRACTED`
- test_auth_backends.py `EXTRACTED`
- auth_tests/test_views.py `EXTRACTED`
- admin_filters/tests.py `EXTRACTED`
- auth_tests/test_forms.py `EXTRACTED`
- admin_inlines/tests.py `EXTRACTED`
- admin_widgets/tests.py `EXTRACTED`
- prefetch_related/tests.py `EXTRACTED`
- model_fields/test_jsonfield.py `EXTRACTED`
- modeladmin/test_checks.py `EXTRACTED`
- migrations/test_commands.py `EXTRACTED`
- urlpatterns_reverse/tests.py `EXTRACTED`

### inherits
- TransactionTestCase `EXTRACTED`
- AggregateTestCase `EXTRACTED`
- ChangeListTests `EXTRACTED`
- LookupTests `EXTRACTED`
- AggregationTests `EXTRACTED`
- Queries1Tests `EXTRACTED`
- ClientTest `EXTRACTED`
- BasicExpressionsTests `EXTRACTED`
- TestQuerying `EXTRACTED`
- QuerySetSetOperationTests `EXTRACTED`
- CaseExpressionTests `EXTRACTED`
- UniqueConstraintTests `EXTRACTED`
- BulkCreateTests `EXTRACTED`
- GenericRelationsTests `EXTRACTED`
- NonAggregateAnnotationTestCase `EXTRACTED`
- ModelFormsetTest `EXTRACTED`
- WindowFunctionTests `EXTRACTED`
- TestInline `EXTRACTED`
- ManyToOneTests `EXTRACTED`
- ListFiltersTests `EXTRACTED`

### method
- .setUpClass() `EXTRACTED`
- ._fixture_setup() `EXTRACTED`
- ._databases_support_transactions() `EXTRACTED`
- ._rollback_atomics() `EXTRACTED`
- ._fixture_teardown() `EXTRACTED`
- ._enter_atomics() `EXTRACTED`
- ._databases_support_savepoints() `EXTRACTED`
- .tearDownClass() `EXTRACTED`
- .setUpTestData() `EXTRACTED`
- ._should_reload_connections() `EXTRACTED`
- .captureOnCommitCallbacks() `EXTRACTED`
- ._should_check_constraints() `EXTRACTED`

### rationale_for
- Similar to TransactionTestCase, but use `transaction.atomic()` to achieve test… `EXTRACTED`

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*