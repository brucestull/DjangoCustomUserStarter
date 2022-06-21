# Django Starter with CustomUser and Docutils
* New project repository which is in active development:
    * [DjangoCustomStarter](https://github.com/brucestull/DjangoCustomStarter)

* NOTE: Author is using PowerShell for this guide.
* NOTE: There is a known issue where this project doesn't run properly on MacBook Air with M1 processor. Maybe something involving django-on-heroku. Changes might be made to accomodate this fact in the new project [DjangoCustomStarter](https://github.com/brucestull/DjangoCustomStarter). 


## Features:
* Custom user model.
* Django admin documentation generator.
* Separate DEV and PROD settings.
* Pipfile included.
* Heroku Procfile included.


## Assumptions:
* User has functioning [Python](https://www.python.org/downloads/) 3.10 installation.
* User has functioning [pipenv](https://pypi.org/project/pipenv/) installation.
* User has functioning [git](https://git-scm.com/downloads) installation.
* User is familiar with how to use terminal commands.
* User has [Heroku](https://www.heroku.com/) account.
* User had [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli#install-the-heroku-cli) installed.

## Process:
1. [Clone DjangoCustomUserStarter Repository](notes/clone_django_custom_user_starter_repo.md)
1. [Create Empty Remote GitHub Repository and Push Existing Application](create_empty_remote_repo_push_existing_application.md)
1. [Run Application Locally](notes/run_application_locally.md)
1. [Create Heroku Application Server Instance](notes/create_heroku_application_server_instance.md)
1. [Add Properties to Heroku Config Vars](notes/add_properties_to_heroku_config_vars.md)
1. [Modify Some Final Production Settings](notes/modify_some_final_production_settings.md)


## Resources:
* CustomUser method: [Django Best Practices: Custom User Model - Will Vincent - LearnDjango](https://learndjango.com/tutorials/django-custom-user-model)
* Docutils: [The Django admin documentation generator](https://docs.djangoproject.com/en/4.0/ref/contrib/admin/admindocs/)
* DjangoCustomUserStarter-archive [Project Board](https://github.com/brucestull/DjangoCustomUserStarter-archive/projects/1)
* DjangoCustomUserStarter-archive [Repository](https://github.com/brucestull/DjangoCustomUserStarter-archive)
