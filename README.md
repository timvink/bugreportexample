Reporting bug:


```
pip install mkdocs==1.2.3 mkdocs-markdownextradata-plugin==0.2.4
mkdocs serve -f "{{ cookiecutter.reponame }}/mkdocs.yml"
```

Will give

```
  File "/home/timvink/miniconda3/lib/python3.9/site-packages/jinja2/environment.py", line 474, in getattr
    return getattr(obj, attribute)
jinja2.exceptions.UndefinedError: 'demo' is undefined
```

