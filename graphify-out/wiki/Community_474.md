# Community 474

> 21 nodes · cohesion 0.16

## Key Concepts

- **PasswordResetTokenGenerator** (18 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **test_tokens.py** (9 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **TokenGeneratorTest** (8 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **.check_token()** (7 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **._make_token_with_timestamp()** (6 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **.make_token()** (5 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **._make_hash_value()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **._num_days()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- **._today()** (3 connections) — `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
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
- **The token is valid after n days, but no greater.** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`
- **A valid token can be created with a secret other than SECRET_KEY by using the…** (1 connections) — `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`

## Relationships

- [Community 49](Community_49.md) (5 shared connections)
- [Community 753](Community_753.md) (2 shared connections)
- [Community 100](Community_100.md) (2 shared connections)
- [Community 22](Community_22.md) (2 shared connections)
- [Community 2](Community_2.md) (2 shared connections)
- [Community 102](Community_102.md) (1 shared connections)
- [Community 58](Community_58.md) (1 shared connections)
- [Community 3](Community_3.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/django-django/django/contrib/auth/tokens.py`
- `raw/code/hyd-evaluation/django-django/tests/auth_tests/test_tokens.py`

## Audit Trail

- EXTRACTED: 47 (96%)
- INFERRED: 2 (4%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*