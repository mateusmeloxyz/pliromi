# pliromi

A treasury web app to track spending and revenue for organizations and institutions, using `Django` and `PostgreSQL`

## Requirements

- `Docker` and `Docker Compose`

## Build and run instructions

- Run

```docker compose up --build```

to build and run both the `Django` web app as well as the `PostgreSQL` database

## Troubleshooting common issues with Docker and Django

Here are some common issues you might encounter and how to solve them:
- Database connection errors: If Django can’t connect to PostgreSQL, verify that your database service name matches in compose.yml and settings.py.
- File synchronization issues: Use the volumes directive in compose.yml to sync changes from your local files to the container.
- Container restart loops or crashes: Use docker compose logs to inspect container errors and determine the cause of the crash.

## Sources

[How to Dockerize a Django App: Step-by-Step Guide for Beginners - By: Lance Haig](https://www.docker.com/blog/how-to-dockerize-django-app/)
