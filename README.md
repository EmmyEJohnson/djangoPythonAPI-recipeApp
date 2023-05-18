# Django and Python Recipe API App
Recipe API Project using Django, Django REST framework, Python, PostgreSQL, Docker, and Swagger UI for the automated documentation for API

Linting:
  Install flake8 package
  Run flake8 through Docker Compose 
      docker-compose run --rm app sh -c "flake8"

Testing:
  Django test suite
  setup tests per django app
  run tests through Docker Compose
      docker-compose run --rm app sh -c "python manage.py test"






Docker:
  Consistent dev and prod environment
  Easier collaboration
  Capture all dependencies as code
    python requirments
    operationg system dependencies
  Easier cleanup

Using Docker Compose:
  Run all commands throuigh Docker Compose
      docker-compose run --rm app sh -c "python manage.py collectstatic"

Using Docker with Django:
  Benefits:
    Consistent dev and prod environment
    Easier collaboration
    Capture all dependencies as code
    Easier cleanup
    Save time
  Drawbacks:
    VSCode unable to access interpreter
    More difficult to use integrated features
    Use terminal