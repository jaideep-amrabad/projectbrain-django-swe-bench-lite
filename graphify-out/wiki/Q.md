# Q

> God node · 232 connections · `raw/code/hyd-evaluation/django-django/django/db/models/query_utils.py`

**Community:** [Community 12](Community_12.md)

## Connections by Relation

### calls
- .test_expressions() `INFERRED`
- .test_filtered_aggregates() `INFERRED`
- .test_invalid_filter() `INFERRED`
- .test_aggregate() `INFERRED`
- ._test_range_overlaps() `INFERRED`
- ._filter_or_exclude() `EXTRACTED`
- .with_perm() `INFERRED`
- .test_case_aggregate() `INFERRED`
- .test_geodetic_distance_lookups() `INFERRED`
- .test_remove_field_check_does_not_remove_meta_constraints() `INFERRED`
- .__init__() `EXTRACTED`
- .delete_batch() `EXTRACTED`
- .test_partial_gin_index() `EXTRACTED`
- .test_partial_gin_index_with_tablespace() `EXTRACTED`
- update_proxy_model_permissions() `INFERRED`
- .test_annotation_disjunction() `INFERRED`
- .test_conditional_aggregate_on_complex_condition() `INFERRED`
- .test_filtered_aggregate_ref_subquery_annotation() `INFERRED`
- .test_combined_q_object() `INFERRED`
- .test_aggregate_subquery_annotation() `INFERRED`

### contains
- query_utils.py `EXTRACTED`

### imports
- expressions.py `EXTRACTED`
- models/query.py `EXTRACTED`
- sql/query.py `EXTRACTED`
- test_indexes.py `EXTRACTED`
- django/db/backends/oracle/operations.py `EXTRACTED`
- indexes/tests.py `EXTRACTED`
- model_indexes/tests.py `EXTRACTED`
- subqueries.py `EXTRACTED`
- models/constraints.py `EXTRACTED`
- models/indexes.py `EXTRACTED`

### method
- ._combine() `EXTRACTED`
- .__init__() `EXTRACTED`
- .__or__() `EXTRACTED`
- .__and__() `EXTRACTED`
- .__invert__() `EXTRACTED`
- .resolve_expression() `EXTRACTED`
- .deconstruct() `EXTRACTED`

### rationale_for
- Encapsulate filters as objects that can then be combined logically (using `&`… `EXTRACTED`

### uses
- When `INFERRED`
- Query `INFERRED`
- QuerySet `INFERRED`
- DatabaseOperations `INFERRED`
- Combinable `INFERRED`
- Index `INFERRED`
- SchemaTests `INFERRED`
- SimpleIndexesTests `INFERRED`
- UniqueConstraint `INFERRED`
- SchemaIndexesPostgreSQLTests `INFERRED`
- UpdateQuery `INFERRED`
- PartialIndexTests `INFERRED`
- DeleteQuery `INFERRED`
- PartialIndexConditionIgnoredTests `INFERRED`

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*