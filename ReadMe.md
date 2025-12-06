# Read Me

## Introduction

This project implements a simple authentication service using JWT (JSON Web Tokens). It provides endpoints for user registration, login, and token validation.

## Installation

```bash
pip install -r requirements.txt
```

## Project structure

This repository contains a Django + Django REST Framework project that implements an OAuth 2.0 authorization server.

```text
.
├── ReadMe.md
├── manage.py               # Django management script
├── myauthservice           # Django project directory
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── oauth2                  # Django app for OAuth 2.0 implementation
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── migrations
│   │   └── __init__.py
│   ├── models.py
│   ├── serializers.py
│   ├── tests.py
│   └── views.py
├── requirements.txt        # Project dependencies
└── tests                   # Test suite
    ├── __init__.py
    └── test_smoke.py
```