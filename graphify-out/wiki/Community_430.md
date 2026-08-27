# Community 430

> 19 nodes · cohesion 0.16

## Key Concepts

- **ProxyDeleteTest** (16 connections) — `raw/code/hyd-evaluation/django-django/tests/delete_regress/tests.py`
- **.create_image()** (8 connections) — `raw/code/hyd-evaluation/django-django/tests/delete_regress/tests.py`
- **Image** (7 connections) — `raw/code/hyd-evaluation/django-django/tests/delete_regress/models.py`
- **Photo** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/delete_regress/models.py`
- **File** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/delete_regress/models.py`
- **FooImage** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/delete_regress/models.py`
- **FooPhoto** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/delete_regress/models.py`
- **Meta** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/delete_regress/models.py`
- **.test_delete_proxy_of_proxy()** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/delete_regress/tests.py`
- **.test_delete_concrete_parent()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/delete_regress/tests.py`
- **.test_delete_proxy()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/delete_regress/tests.py`
- **.test_delete_proxy_pair()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/delete_regress/tests.py`
- **.test_19187_values()** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/delete_regress/tests.py`
- **Tests on_delete behavior for proxy models. See #16128.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/delete_regress/tests.py`
- **Return an Image referenced by both a FooImage and a FooFile.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/delete_regress/tests.py`
- **Deleting the *proxy* instance bubbles through to its non-proxy and *all*…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/delete_regress/tests.py`
- **Deleting a proxy-of-proxy instance should bubble through to its proxy and non-…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/delete_regress/tests.py`
- **Deleting an instance of a concrete model should also delete objects referencing…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/delete_regress/tests.py`
- **If a pair of proxy models are linked by an FK from one concrete parent to the…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/delete_regress/tests.py`

## Relationships

- [Community 141](Community_141.md) (16 shared connections)
- [Community 36](Community_36.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/tests/delete_regress/models.py`
- `raw/code/hyd-evaluation/django-django/tests/delete_regress/tests.py`

## Audit Trail

- EXTRACTED: 37 (84%)
- INFERRED: 7 (16%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*