# Community 498

> 20 nodes · cohesion 0.16

## Key Concepts

- **PasswordResetTokenGenerator** (21 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **TokenGeneratorTest** (8 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.check_token()** (7 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **._make_token_with_timestamp()** (6 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **.make_token()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **._num_seconds()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **._make_hash_value()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **._now()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **.test_10265()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.test_timeout()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.test_token_with_different_secret()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.test_check_token_with_nonexistent_token_and_user()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.test_make_token()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **Return a token that can be used once to do a password reset for the given user.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **Check that a password reset token is correct for a given user.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **Hash the user's primary key and some user state that's sure to change after a…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **Strategy object used to generate and check tokens for the password reset…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **The token generated for a user created in the same request will work correctly.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **The token is valid after n seconds, but no greater.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **A valid token can be created with a secret other than SECRET_KEY by using the…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`

## Relationships

- [Community 4](Community_4.md) (4 shared connections)
- [Community 549](Community_549.md) (2 shared connections)
- [Community 431](Community_431.md) (2 shared connections)
- [Community 714](Community_714.md) (2 shared connections)
- [Community 1](Community_1.md) (1 shared connections)
- [Community 142](Community_142.md) (1 shared connections)
- [Community 225](Community_225.md) (1 shared connections)
- [Community 665](Community_665.md) (1 shared connections)
- [Community 26](Community_26.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`

## Audit Trail

- EXTRACTED: 42 (91%)
- INFERRED: 4 (9%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*