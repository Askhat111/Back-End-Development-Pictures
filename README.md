# Back-End-Development-Pictures

Pictures Flask REST API — IBM Back-end Application Development Capstone Project.

Public repository: https://github.com/Askhat111/Back-End-Development-Pictures

Direct README URL: https://github.com/Askhat111/Back-End-Development-Pictures/blob/main/README.md

## Source and execution

Full application source, original directories, tests, templates and assets are in `source.zip`. Extract with `python -m zipfile -e source.zip .`, then install `requirements.txt`. The root Dockerfile extracts this source during the build. Original IBM Developer Skills Network starter attribution and license notices are preserved.

## Verified results

11 supplied PyTest tests passed in the IBM lab. Endpoints: /health, /count, /picture, /picture/<id>. Supports GET, POST, PUT and DELETE.

Deployment: https://pictures.2gndqglho9ku.us-south.codeengine.appdomain.cloud

Validation date: 2026-11-01. These are temporary Skills Network lab deployments and may expire with the lab session. Terminal outputs and browser screenshots are separate submission evidence.

## Configuration

Songs uses `MONGODB_URI` or `MONGODB_SERVICE` and `MONGODB_PORT`. Django uses `SONGS_API_URL`, `PICTURES_API_URL`, `DJANGO_ALLOWED_HOSTS`, `DJANGO_SECRET_KEY`, `DJANGO_CSRF_TRUSTED_ORIGINS` and `DJANGO_TRUST_PROXY_HEADERS`. Only enable proxy-header trust behind the trusted deployment ingress. Do not commit credentials.
