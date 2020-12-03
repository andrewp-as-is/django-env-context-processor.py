<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/django-env-context-processor.svg?maxAge=3600)](https://pypi.org/project/django-env-context-processor/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/django-env-context-processor.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/django-env-context-processor.py/actions)

### Installation
```bash
$ [sudo] pip install django-env-context-processor
```

##### `settings.py`
```python
TEMPLATES = [
    {
        # …
        'OPTIONS': {
            'context_processors': [
                'django_env_context_processor.context_processors.env',
            ],
        },
    },
]
```

##### `.env`
```bash
export ENV_VARIABLE=42
```

##### Templates
```html
{{ ENV_VARIABLE }}
```

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>
