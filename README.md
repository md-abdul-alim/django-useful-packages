# django-useful-packages

# [CREATE README FILE](https://dillinger.io/)
[DJANGO TOP 10 MISTAKES](https://www.toptal.com/django/django-top-10-mistakes)
## pip-tools :
[![pip-tools](https://warehouse-camo.ingress.cmh1.psfhosted.org/26735b1ff04e09389d56437a16df0d1bb0f725da/68747470733a2f2f6769746875622e636f6d2f6a617a7a62616e642f7069702d746f6f6c732f7261772f6d61737465722f696d672f7069702d746f6f6c732d6f766572766965772e737667)](https://pypi.org/project/pip-tools/)

[![Medium documentation](https://miro.medium.com/1*m-R_BkNf1Qjr1YbyOIJY2w.png)](https://suyojtamrakar.medium.com/managing-your-requirements-txt-with-pip-tools-in-python-8d07d9dfa464)
- Create a requirements.in file
  - add packages manually. 
  - or `pip freeze > requirements.in`
- Now run bellow command for creating requirements.txt file
  - `pip-compile`
    - >pip-compile automatic create requirements.txt file
  - `pip-compile requirements.in`
- now for installing all packages from requirements.txt run 
  - `pip-sync`
  - or `pip-sync requirements.txt`


## django-split-settings :
[![django-split-settings](https://warehouse-camo.ingress.cmh1.psfhosted.org/9ff9c349705260118a57294a8b075326e07ba2ad/68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f736f626f6c65766e2f646a616e676f2d73706c69742d73657474696e67732f6d61737465722f646f63732f5f7374617469632f6c6f676f2d626c61636b2e706e67)](https://pypi.org/project/django-split-settings/)

[Django split settings](https://django-split-settings.readthedocs.io/en/latest/index.html)
  - > Setting calling point inside settings folder -> __ init __.py


## django-extensions :
[Django Extensions](https://pypi.org/project/django-extensions/#description)

[Documentation](https://django-extensions.readthedocs.io/en/latest/)
- Create a requirements.in file
  - Admin extensions
  - Command extensions
    - shell activity
    - dump script
    - settings
    - generate password
    - reset db
    - sync s3 bucket
  - Jobs Scheduling


## Jobs Scheduling package :
- [Celery](https://pypi.org/project/celery/)

[![Celery](https://warehouse-camo.ingress.cmh1.psfhosted.org/b1336bf90c555ca9b45aca49e9d2b51a00783c1c/687474703a2f2f646f63732e63656c65727970726f6a6563742e6f72672f656e2f6c61746573742f5f696d616765732f63656c6572792d62616e6e65722d736d616c6c2e706e67)](https://docs.celeryq.dev/en/stable/index.html)

- [Django Q](https://pypi.org/project/django-q/)

[![Celery](https://django-q.readthedocs.io/en/latest/_static/logo.png)](https://django-q.readthedocs.io/en/latest/)

- [Django Celery](https://pypi.org/project/django-celery/)

[![Django Celery](https://warehouse-camo.ingress.cmh1.psfhosted.org/43b9145dabc2d3ba875afea386fa5629ab5db9df/68747470733a2f2f757365722d696d616765732e67697468756275736572636f6e74656e742e636f6d2f32363333362f35393131333838312d39313763353138302d383930622d313165392d393836332d6635613938643065323335652e706e67)](https://docs.celeryq.dev/en/latest/django/first-steps-with-django.html)

[Tutorial]: <https://django.cowhite.com/blog/scheduling-taks-in-django/>
