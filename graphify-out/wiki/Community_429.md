# Community 429

> 26 nodes · cohesion 0.12

## Key Concepts

- **PasswordResetTokenGenerator** (20 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **TokenGeneratorTest** (9 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.check_token()** (7 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **._make_token_with_timestamp()** (6 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **MockedPasswordResetTokenGenerator** (6 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.make_token()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **._num_seconds()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **._make_hash_value()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **._now()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **.test_10265()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.test_timeout()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.test_token_with_different_email()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.test_token_with_different_secret()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.test_check_token_with_nonexistent_token_and_user()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.test_make_token()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.__init__()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **Return a token that can be used once to do a password reset for the given user.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **Check that a password reset token is correct for a given user.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **Hash the user's primary key, email (if available), and some user state that's…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **Strategy object used to generate and check tokens for the password reset…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **.__init__()** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **._now()** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **The token generated for a user created in the same request will work correctly.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **Updating the user email address invalidates the token.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **The token is valid after n seconds, but no greater.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- *... and 1 more nodes in this community*

## Relationships

- [Community 451](Community_451.md) (3 shared connections)
- [Community 33](Community_33.md) (3 shared connections)
- [Community 0](Community_0.md) (2 shared connections)
- [Community 734](Community_734.md) (2 shared connections)
- [Community 239](Community_239.md) (1 shared connections)
- [Community 623](Community_623.md) (1 shared connections)
- [Community 110](Community_110.md) (1 shared connections)
- [Community 18](Community_18.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`

## Audit Trail

- EXTRACTED: 49 (94%)
- INFERRED: 3 (6%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*