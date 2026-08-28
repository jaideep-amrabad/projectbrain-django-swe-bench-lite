# TestCase

> God node · 1036 connections · `raw/code/hyd-evaluation/django-django/django/test/testcases.py`

**Community:** [Community 48](Community_48.md)

## Connections by Relation

### contains
- testcases.py `EXTRACTED`

### imports
- django/test/__init__.py `EXTRACTED`
- queries/tests.py `EXTRACTED`
- model_forms/tests.py `EXTRACTED`
- cache/tests.py `EXTRACTED`
- admin_changelist/tests.py `EXTRACTED`
- i18n/tests.py `EXTRACTED`
- test_utils/tests.py `EXTRACTED`
- expressions/tests.py `EXTRACTED`
- auth_tests/test_views.py `EXTRACTED`
- admin_scripts/tests.py `EXTRACTED`
- test_auth_backends.py `EXTRACTED`
- admin_widgets/tests.py `EXTRACTED`
- admin_filters/tests.py `EXTRACTED`
- prefetch_related/tests.py `EXTRACTED`
- admin_inlines/tests.py `EXTRACTED`
- urlpatterns_reverse/tests.py `EXTRACTED`
- fixtures_regress/tests.py `EXTRACTED`
- auth_tests/test_forms.py `EXTRACTED`
- sessions_tests/tests.py `EXTRACTED`
- test_client_regress/tests.py `EXTRACTED`

### inherits
- TransactionTestCase `EXTRACTED`
- AggregateTestCase `EXTRACTED`
- ChangeListTests `EXTRACTED`
- Queries1Tests `EXTRACTED`
- ClientTest `EXTRACTED`
- CaseExpressionTests `EXTRACTED`
- AggregationTests `EXTRACTED`
- BasicExpressionsTests `EXTRACTED`
- TestQuerying `EXTRACTED`
- ModelFormsetTest `EXTRACTED`
- NonAggregateAnnotationTestCase `EXTRACTED`
- BulkCreateTests `EXTRACTED`
- GenericRelationsTests `EXTRACTED`
- QuerySetSetOperationTests `EXTRACTED`
- LookupTests `EXTRACTED`
- TestInline `EXTRACTED`
- WindowFunctionTests `EXTRACTED`
- ModelInheritanceTest `EXTRACTED`
- ListFiltersTests `EXTRACTED`
- ManyToOneTests `EXTRACTED`

### method
- .setUpClass() `EXTRACTED`
- ._databases_support_transactions() `EXTRACTED`
- ._rollback_atomics() `EXTRACTED`
- ._fixture_teardown() `EXTRACTED`
- ._enter_atomics() `EXTRACTED`
- ._fixture_setup() `EXTRACTED`
- .setUpTestData() `EXTRACTED`
- .tearDownClass() `EXTRACTED`
- ._should_reload_connections() `EXTRACTED`
- .captureOnCommitCallbacks() `EXTRACTED`
- ._should_check_constraints() `EXTRACTED`

### rationale_for
- Similar to TransactionTestCase, but use `transaction.atomic()` to achieve test… `EXTRACTED`

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*