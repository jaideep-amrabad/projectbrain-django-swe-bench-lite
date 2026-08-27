# Community 336

> 32 nodes · cohesion 0.10

## Key Concepts

- **GZipMiddleware** (20 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/gzip.py`
- **GZipMiddlewareTest** (16 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **ETagGZipMiddlewareTest** (8 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **.decompress()** (7 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **.test_etag_match()** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **.test_compress_file_response()** (5 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **.test_strong_etag_modified()** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **.test_weak_etag_not_modified()** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **.test_compress_deterministic()** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **.test_compress_non_200_response()** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **.test_compress_response()** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **.test_compress_streaming_response()** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **.test_compress_streaming_response_unicode()** (4 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **.get_mtime()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **.setUp()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **.test_no_compress_compressed_response()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **.test_no_compress_incompressible_response()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **.test_no_compress_short_response()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **Compression is performed on responses with streaming content.** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **Compress content if the browser allows gzip compression. Set the Vary header…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/middleware/gzip.py`
- **Tests the GZipMiddleware.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **Compression is performed on responses with compressible content.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **Compression is performed on FileResponse.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **Compression is performed on responses with a status other than 200 (#10762).** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- **Compression isn't performed on responses with short content.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`
- *... and 7 more nodes in this community*

## Relationships

- [Community 1](Community_1.md) (5 shared connections)
- [Community 23](Community_23.md) (4 shared connections)
- [Community 263](Community_263.md) (2 shared connections)
- [Community 3](Community_3.md) (2 shared connections)
- [Community 347](Community_347.md) (2 shared connections)
- [Community 298](Community_298.md) (2 shared connections)
- [Community 153](Community_153.md) (1 shared connections)
- [Community 112](Community_112.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/middleware/gzip.py`
- `raw/code/hyd-evaluation/django-django/tests/middleware/tests.py`

## Audit Trail

- EXTRACTED: 64 (93%)
- INFERRED: 5 (7%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*