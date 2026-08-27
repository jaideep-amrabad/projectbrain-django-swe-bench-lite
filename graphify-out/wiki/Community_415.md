# Community 415

> 19 nodes · cohesion 0.18

## Key Concepts

- **PasswordResetTokenGenerator** (23 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **TokenGeneratorTest** (11 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.check_token()** (7 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **._make_token_with_timestamp()** (6 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **.make_token()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **._num_seconds()** (4 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **._make_hash_value()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **._now()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **.test_token_default_hashing_algorithm()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.test_token_with_different_secret()** (3 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.test_check_token_with_nonexistent_token_and_user()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.test_legacy_token_validation()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.test_make_token()** (2 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.__init__()** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **Return a token that can be used once to do a password reset for the given user.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **Check that a password reset token is correct for a given user.** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **Hash the user's primary key and some user state that's sure to change after a…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **Strategy object used to generate and check tokens for the password reset…** (1 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **A valid token can be created with a secret other than SECRET_KEY by using the…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`

## Relationships

- [Community 26](Community_26.md) (7 shared connections)
- [Community 70](Community_70.md) (4 shared connections)
- [Community 1681](Community_1681.md) (3 shared connections)
- [Community 701](Community_701.md) (2 shared connections)
- [Community 123](Community_123.md) (1 shared connections)
- [Community 379](Community_379.md) (1 shared connections)
- [Community 21](Community_21.md) (1 shared connections)
- [Community 389](Community_389.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`

## Audit Trail

- EXTRACTED: 45 (90%)
- INFERRED: 5 (10%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*