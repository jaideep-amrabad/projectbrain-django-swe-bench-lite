# TestCase

> God node · 1000 connections · `raw/code/hyd-evaluation/django-django/django/test/testcases.py`

**Community:** [Community 19](Community_19.md)

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
- expressions/tests.py `EXTRACTED`
- test_utils/tests.py `EXTRACTED`
- test_auth_backends.py `EXTRACTED`
- auth_tests/test_views.py `EXTRACTED`
- admin_scripts/tests.py `EXTRACTED`
- admin_widgets/tests.py `EXTRACTED`
- admin_filters/tests.py `EXTRACTED`
- urlpatterns_reverse/tests.py `EXTRACTED`
- admin_inlines/tests.py `EXTRACTED`
- prefetch_related/tests.py `EXTRACTED`
- fixtures_regress/tests.py `EXTRACTED`
- test_client_regress/tests.py `EXTRACTED`
- sessions_tests/tests.py `EXTRACTED`
- auth_tests/test_forms.py `EXTRACTED`

### inherits
- AutodetectorTests `EXTRACTED`
- TransactionTestCase `EXTRACTED`
- ChangeListTests `EXTRACTED`
- AggregateTestCase `EXTRACTED`
- Queries1Tests `EXTRACTED`
- ClientTest `EXTRACTED`
- CaseExpressionTests `EXTRACTED`
- BasicExpressionsTests `EXTRACTED`
- AggregationTests `EXTRACTED`
- TestQuerying `EXTRACTED`
- ModelFormsetTest `EXTRACTED`
- LookupTests `EXTRACTED`
- NonAggregateAnnotationTestCase `EXTRACTED`
- GenericRelationsTests `EXTRACTED`
- ModelInheritanceTest `EXTRACTED`
- ModelFormBaseTest `EXTRACTED`
- ListFiltersTests `EXTRACTED`
- ManyToOneTests `EXTRACTED`
- TestInline `EXTRACTED`
- PostgreSQLTestCase `EXTRACTED`

### method
- .setUpClass() `EXTRACTED`
- ._databases_support_transactions() `EXTRACTED`
- ._rollback_atomics() `EXTRACTED`
- .tearDownClass() `EXTRACTED`
- ._fixture_teardown() `EXTRACTED`
- ._enter_atomics() `EXTRACTED`
- ._fixture_setup() `EXTRACTED`
- .setUpTestData() `EXTRACTED`
- ._should_reload_connections() `EXTRACTED`
- ._should_check_constraints() `EXTRACTED`
- .captureOnCommitCallbacks() `EXTRACTED`

### rationale_for
- Similar to TransactionTestCase, but use `transaction.atomic()` to achieve test… `EXTRACTED`

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*