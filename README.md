# FastAPI Users - Database adapter for SQLAlchemy ORM

<p align="center">
  <img src="https://raw.githubusercontent.com/frankie567/fastapi-users/master/logo.svg?sanitize=true" alt="FastAPI Users">
</p>

<p align="center">
    <em>Ready-to-use and customizable users management for FastAPI</em>
</p>

[![build](https://github.com/fastapi-users/fastapi-users-db-sqlalchemy/workflows/Build/badge.svg)](https://github.com/fastapi-users/fastapi-users/actions)
[![codecov](https://codecov.io/gh/fastapi-users/fastapi-users-db-sqlalchemy/branch/master/graph/badge.svg)](https://codecov.io/gh/fastapi-users/fastapi-users-db-sqlalchemy)
[![PyPI version](https://badge.fury.io/py/fastapi-users-db-sqlalchemy.svg)](https://badge.fury.io/py/fastapi-users-db-sqlalchemy)
[![Downloads](https://pepy.tech/badge/fastapi-users-db-sqlalchemy)](https://pepy.tech/project/fastapi-users-db-sqlalchemy)
<p align="center">
<a href="https://github.com/sponsors/frankie567"><img src="https://md-buttons.onrender.com/button.svg?text=Buy%20me%20a%20coffee%20%E2%98%95%EF%B8%8F&bg=ef4444&w=200&px=40"></a>
</p>

---

**Documentation**: <a href="https://fastapi-users.github.io/fastapi-users/" target="_blank">https://fastapi-users.github.io/fastapi-users/</a>

**Source Code**: <a href="https://github.com/fastapi-users/fastapi-users" target="_blank">https://github.com/fastapi-users/fastapi-users</a>

---

Add quickly a registration and authentication system to your [FastAPI](https://fastapi.tiangolo.com/) project. **FastAPI Users** is designed to be as customizable and adaptable as possible.

**Sub-package for SQLAlchemy ORM support in FastAPI Users.**

## Development

### Setup environment

You should create a virtual environment and activate it:

```bash
python -m venv venv/
```

```bash
source venv/bin/activate
```

And then install the development dependencies:

```bash
pip install -r requirements.dev.txt
```

### Run unit tests

You can run all the tests with:

```bash
make test
```

Alternatively, you can run `pytest` yourself:

```bash
pytest
```

There are quite a few unit tests, so you might run into ulimit issues where there are too many open file descriptors. You may be able to set a new, higher limit temporarily with:

```bash
ulimit -n 2048
```

### Format the code

Execute the following command to apply `isort` and `black` formatting:

```bash
make format
```

## License

This project is licensed under the terms of the MIT license.
