# Nauts.io website

## How to run locally
```
docker run --rm --name=nautsio --volume=$(pwd):/srv/jekyll -it -p 4000:4000 jekyll/jekyll:pages jekyll serve --force_polling
```
