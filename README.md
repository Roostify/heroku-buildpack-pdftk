# heroku-buildpack-pdftk
Public heroku buildpack on github setup to be used in the heroku deployments

# Usage
- Add https://github.com/Roostify/heroku-buildpack-pdftk url in .buildpack file in your project.
- Add below ENV variables in Heroku
```
LD_LIBRARY_PATH=/app/.heroku/vendor/lib:/app/vendor/pdftk/lib
PATH=/app/.heroku/python/bin:/usr/local/bin:/usr/bin:/bin:/app/vendor/pdftk/bin
```
