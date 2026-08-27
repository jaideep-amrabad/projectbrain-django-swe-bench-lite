# TestCase

> God node · 973 connections · `raw/code/hyd-evaluation/django-django/django/test/testcases.py`

**Community:** [Community 600](Community_600.md)

## Connections by Relation

### contains
- testcases.py `EXTRACTED`

### imports
- django/test/__init__.py `EXTRACTED`
- queries/tests.py `EXTRACTED`
- model_forms/tests.py `EXTRACTED`
- i18n/tests.py `EXTRACTED`
- admin_changelist/tests.py `EXTRACTED`
- cache/tests.py `EXTRACTED`
- expressions/tests.py `EXTRACTED`
- auth_tests/test_views.py `EXTRACTED`
- test_utils/tests.py `EXTRACTED`
- test_auth_backends.py `EXTRACTED`
- admin_widgets/tests.py `EXTRACTED`
- admin_filters/tests.py `EXTRACTED`
- admin_scripts/tests.py `EXTRACTED`
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
- Queries1Tests `EXTRACTED`
- ClientTest `EXTRACTED`
- CaseExpressionTests `EXTRACTED`
- AggregateTestCase `EXTRACTED`
- AggregationTests `EXTRACTED`
- BasicExpressionsTests `EXTRACTED`
- ModelFormsetTest `EXTRACTED`
- ModelInheritanceTest `EXTRACTED`
- GenericRelationsTests `EXTRACTED`
- ModelFormBaseTest `EXTRACTED`
- TestQuerying `EXTRACTED`
- ManyToOneTests `EXTRACTED`
- TestInline `EXTRACTED`
- NonAggregateAnnotationTestCase `EXTRACTED`
- LookupTests `EXTRACTED`
- GenericRelationTests `EXTRACTED`
- OneToOneTests `EXTRACTED`

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

### rationale_for
- Similar to TransactionTestCase, but use `transaction.atomic()` to achieve test… `EXTRACTED`

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*