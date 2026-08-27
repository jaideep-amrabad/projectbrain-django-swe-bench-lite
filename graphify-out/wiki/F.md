# F

> God node · 327 connections · `raw/code/hyd-evaluation/django-django/django/db/models/expressions.py`

**Community:** [Community 26](Community_26.md)

## Connections by Relation

### calls
- .test_expressions() `EXTRACTED`
- .test_invalid_filter() `EXTRACTED`
- .test_subquery_row_range_rank() `EXTRACTED`
- .test_aggregate() `EXTRACTED`
- ._parse_expressions() `EXTRACTED`
- .dates() `EXTRACTED`
- .test_custom_functions_can_ref_other_functions() `EXTRACTED`
- .test_annotate_with_aggregation_in_condition() `EXTRACTED`
- ._test_range_overlaps() `EXTRACTED`
- .datetimes() `EXTRACTED`
- .test_case_aggregate() `EXTRACTED`
- .test_custom_functions() `EXTRACTED`
- .test_extract_year_exact_lookup() `EXTRACTED`
- .test_annotate_with_in_clause() `EXTRACTED`
- .test_filter_with_aggregation_in_condition() `EXTRACTED`
- .test_fail_insert() `EXTRACTED`
- .test_multiple_partitioning() `EXTRACTED`
- .test_postgresql_illegal_range_frame_end() `EXTRACTED`
- .test_postgresql_illegal_range_frame_start() `EXTRACTED`
- .test_range_n_preceding_and_following() `EXTRACTED`

### contains
- expressions.py `EXTRACTED`

### imports
- django/db/models/__init__.py `EXTRACTED`
- queries/tests.py `EXTRACTED`
- admin_changelist/tests.py `EXTRACTED`
- expressions/tests.py `EXTRACTED`
- models/query.py `EXTRACTED`
- sql/query.py `EXTRACTED`
- modeladmin/test_checks.py `EXTRACTED`
- timezones/tests.py `EXTRACTED`
- admin/checks.py `EXTRACTED`
- test_extract_trunc.py `EXTRACTED`
- expressions_window/tests.py `EXTRACTED`
- main.py `EXTRACTED`
- aggregation_regress/tests.py `EXTRACTED`
- test_ranges.py `EXTRACTED`
- distapp/tests.py `EXTRACTED`
- annotations/tests.py `EXTRACTED`
- aggregation/tests.py `EXTRACTED`
- test_query.py `EXTRACTED`
- test_search.py `EXTRACTED`
- queries/test_bulk_update.py `EXTRACTED`

### inherits
- OuterRef `EXTRACTED`
- Combinable `EXTRACTED`
- ResolvedOuterRef `EXTRACTED`

### method
- .__init__() `EXTRACTED`
- .asc() `EXTRACTED`
- .desc() `EXTRACTED`
- .__repr__() `EXTRACTED`
- .resolve_expression() `EXTRACTED`
- .__eq__() `EXTRACTED`
- .__hash__() `EXTRACTED`

### rationale_for
- An object capable of resolving references to existing query objects. `EXTRACTED`

### references
- deconstructible() `EXTRACTED`

### uses
- Query `INFERRED`
- QuerySet `INFERRED`
- BasicExpressionsTests `INFERRED`
- TestGeneralAggregate `INFERRED`
- BaseModelAdminChecks `INFERRED`
- TestStatisticsAggregate `INFERRED`
- ChangeList `INFERRED`
- FTimeDeltaTests `INFERRED`
- ExpressionOperatorTests `INFERRED`
- ReprTests `INFERRED`
- IterableLookupInnerExpressionsTests `INFERRED`
- OrderableAggMixin `INFERRED`
- ValuesExpressionsTests `INFERRED`
- DecimalFieldLookupTests `INFERRED`
- ExpressionsNumericTests `INFERRED`
- ExpressionsTests `INFERRED`
- FTests `INFERRED`

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*