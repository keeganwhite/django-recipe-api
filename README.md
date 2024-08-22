# Django Recipe API
Demo project showcasing Django, and development best practices such as unit tests, GitHub actions and flake8.

## Commands

### Docker Compose Run Commands
* run flake8 in your docker container: `docker compose run --rm app sh -c "flake8"`
* run unit tests in your docker container: `docker compose run --rm app sh -c "python manage.py test"`