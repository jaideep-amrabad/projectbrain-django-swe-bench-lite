# HttpRequest

> God node · 242 connections · `raw/code/hyd-evaluation/django-django/django/http/request.py`

**Community:** [Community 23](Community_23.md)

## Connections by Relation

### calls
- .get_request() `EXTRACTED`
- .get_request() `EXTRACTED`
- .test_tz_template_context_processor() `EXTRACTED`
- .test_login_csrf_rotate() `EXTRACTED`
- .test_default_logout_then_login() `EXTRACTED`
- .test_defaults_sameorigin() `EXTRACTED`
- .test_deny() `EXTRACTED`
- .test_dont_set_if_set() `EXTRACTED`
- .test_response_exempt() `EXTRACTED`
- .test_same_origin() `EXTRACTED`
- .test_conditional_content_removal() `EXTRACTED`
- .login() `EXTRACTED`
- .logout() `EXTRACTED`
- .test_changed_backend_settings() `EXTRACTED`
- .test_logout_then_login_with_custom_login() `EXTRACTED`
- .test_get_cache_key() `EXTRACTED`
- .test_get_cache_key_with_query() `EXTRACTED`
- .test_cache_control_decorator_http_request_proxy() `EXTRACTED`
- .test_never_cache_decorator_http_request_proxy() `EXTRACTED`
- .test_is_extendable() `EXTRACTED`

### contains
- request.py `EXTRACTED`

### imports
- http/__init__.py `EXTRACTED`
- cache/tests.py `EXTRACTED`
- test/client.py `EXTRACTED`
- auth_tests/test_views.py `EXTRACTED`
- test_auth_backends.py `EXTRACTED`
- urlpatterns_reverse/tests.py `EXTRACTED`
- timezones/tests.py `EXTRACTED`
- decorators/tests.py `EXTRACTED`
- test_middleware_mixin.py `EXTRACTED`
- auth_tests/urls.py `EXTRACTED`
- requests_tests/tests.py `EXTRACTED`
- sites_tests/tests.py `EXTRACTED`
- handlers/wsgi.py `EXTRACTED`
- middleware/tests.py `EXTRACTED`
- settings_tests/tests.py `EXTRACTED`
- contenttypes_tests/test_views.py `EXTRACTED`
- asgi.py `EXTRACTED`
- csrf_tests/tests.py `EXTRACTED`
- requests/tests.py `EXTRACTED`
- messages_tests/base.py `EXTRACTED`

### inherits
- WSGIRequest `EXTRACTED`
- ASGIRequest `EXTRACTED`
- TestingHttpRequest `EXTRACTED`

### method
- ._load_post_and_files() `EXTRACTED`
- .get_host() `EXTRACTED`
- .get_full_path() `EXTRACTED`
- .body() `EXTRACTED`
- ._get_raw_host() `EXTRACTED`
- .parse_file_upload() `EXTRACTED`
- .get_raw_uri() `EXTRACTED`
- .build_absolute_uri() `EXTRACTED`
- ._mark_post_parse_error() `EXTRACTED`
- .get_port() `EXTRACTED`
- ._get_scheme() `EXTRACTED`
- .scheme() `EXTRACTED`
- .encoding() `EXTRACTED`
- .upload_handlers() `EXTRACTED`
- .read() `EXTRACTED`
- .__init__() `EXTRACTED`
- .get_signed_cookie() `EXTRACTED`
- ._current_scheme_host() `EXTRACTED`
- .is_secure() `EXTRACTED`
- ._initialize_handlers() `EXTRACTED`

### rationale_for
- A basic HTTP request. `EXTRACTED`

### uses
- cached_property `INFERRED`
- MultiPartParser `INFERRED`
- MiddlewareMixinTests `INFERRED`
- MultiPartParserError `INFERRED`
- good_handler_deferred_annotations() `INFERRED`

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*