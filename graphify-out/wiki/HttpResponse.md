# HttpResponse

> God node · 336 connections · `raw/code/hyd-evaluation/django-django/django/http/response.py`

**Community:** [Community 21](Community_21.md)

## Connections by Relation

### calls
- render() `EXTRACTED`
- post_form_view() `EXTRACTED`
- token_view() `EXTRACTED`
- technical_500_response() `EXTRACTED`
- empty_view() `EXTRACTED`
- set_language() `EXTRACTED`
- ensure_csrf_cookie_view() `EXTRACTED`
- .get_response() `EXTRACTED`
- render_flatpage() `EXTRACTED`
- render_to_kmz() `EXTRACTED`
- .my_view() `EXTRACTED`
- trace_view() `EXTRACTED`
- default_urlconf() `EXTRACTED`
- non_token_view_using_request_processor() `EXTRACTED`
- get_view() `EXTRACTED`
- post_view() `EXTRACTED`
- render_to_kml() `EXTRACTED`
- .__call__() `EXTRACTED`
- directory_index() `EXTRACTED`
- remote_user_auth_view() `EXTRACTED`

### contains
- http/response.py `EXTRACTED`

### imports
- admin_views/admin.py `EXTRACTED`
- http/__init__.py `EXTRACTED`
- cache/tests.py `EXTRACTED`
- test_utils/tests.py `EXTRACTED`
- test_client/views.py `EXTRACTED`
- test_client_regress/tests.py `EXTRACTED`
- view_tests/views.py `EXTRACTED`
- sessions_tests/tests.py `EXTRACTED`
- utils/cache.py `EXTRACTED`
- decorators/tests.py `EXTRACTED`
- test_middleware_mixin.py `EXTRACTED`
- views/debug.py `EXTRACTED`
- test_client_regress/views.py `EXTRACTED`
- auth_tests/urls.py `EXTRACTED`
- sites_tests/tests.py `EXTRACTED`
- urlpatterns_reverse/views.py `EXTRACTED`
- django/shortcuts.py `EXTRACTED`
- asgi/tests.py `EXTRACTED`
- generic_views/test_base.py `EXTRACTED`
- httpwrappers/tests.py `EXTRACTED`

### inherits
- HttpResponseBase `EXTRACTED`
- SimpleTemplateResponse `EXTRACTED`
- JsonResponse `EXTRACTED`
- HttpResponseNotFound `EXTRACTED`
- HttpResponseNotAllowed `EXTRACTED`
- HttpResponseNotModified `EXTRACTED`
- HttpResponseServerError `EXTRACTED`
- HttpResponseBadRequest `EXTRACTED`
- HttpResponseForbidden `EXTRACTED`
- HttpResponseGone `EXTRACTED`
- HttpResponseRedirectBase `EXTRACTED`

### method
- .serialize() `EXTRACTED`
- .content() `EXTRACTED`
- .write() `EXTRACTED`
- .__init__() `EXTRACTED`
- .writelines() `EXTRACTED`
- .__repr__() `EXTRACTED`
- .__iter__() `EXTRACTED`
- .tell() `EXTRACTED`
- .getvalue() `EXTRACTED`
- .writable() `EXTRACTED`

### rationale_for
- An HTTP response class with a string as content. This content that can be read,… `EXTRACTED`

### uses
- MiddlewareMixinTests `INFERRED`

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*