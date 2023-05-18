# Django and Python Recipe API App
Recipe API Project using Django, Django REST framework, Python, PostgreSQL, Docker, and Swagger UI for the automated documentation for API


# Linting:

    docker-compose run --rm app sh -c "flake8"

  - Install flake8 package
  - Run flake8 through Docker Compose 

# Create Django Project with Docker Compose:

    docker-compose run --rm app sh -c "django-admin startproject app ."

# Testing:

    docker-compose run --rm app sh -c "python manage.py test"

  - Django test suite
  - Setup tests per django app
  - Run tests through Docker Compose







# Docker:
  - Consistent dev and prod environment
  - Easier collaboration
  - Capture all dependencies as code
    python requirments
    operationg system dependencies
  - Easier cleanup

# Using Docker Compose:

    docker-compose run --rm app sh -c "python manage.py collectstatic"

  - Run all commands throuigh Docker Compose

# Using Docker with Django:

  Benefits:
  - Consistent dev and prod environment
  - Easier collaboration
  - Capture all dependencies as code
  - Easier cleanup
  - Save time

  Drawbacks:
  - VSCode unable to access interpreter
  - More difficult to use integrated features
  - Use terminal