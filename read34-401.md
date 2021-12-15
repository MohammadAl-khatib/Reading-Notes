# API Deployment

## Django Settings Best Practices

### Managing Django Settings: Issues

- Different environments: during the project life, it will meet multiple environments, each one with its own configuration and settings.
- Sensitive data
- Sharing settings between team members: some team members may have problems configuring their settings
- Django settings are a Python code

### Approaches of handling settings
1. using settings_local.py

    This file is automatically ignored by VCS (version control system).

    **Pros:**

    Secrets not in VCS.

    **Cons:**

    settings_local.py is not in VCS, so you can lose some of your Django environment settings.

    The Django settings file is a Python code, so settings_local.py can have some non-obvious logic.

    You need to have settings_local.example (in VCS) to share the default configurations for developers.

2. Separate settings file for each environment

    Here you will define a settings file for each environment, and use the file when it is needed using `python manage.py runserver --settings = file name`

    **Pros:**

    All environments are in VCS.

    It’s easy to share settings between developers.

    **Cons:**

    You need to find a way to handle secret passwords and tokens.

    “Inheritance” of settings can be hard to trace and maintain.

3. Environment variables

    Using `os.environ` to store sensitive data

    **Pros:**

    Configuration is separated from code.

    Environment parity – you have the same code for all environments.

    No inheritance in settings, and cleaner and more consistent code.

    There is a theoretical grounding for using environment variables – 12 Factors.

    **Cons:**

    You need to handle sharing default config between developers.

    And other approachs which can be found [here](https://djangostars.com/blog/configuring-django-settings-best-practices/)

## SSH Tutorial

