## The AI4SE website

The AI4SE web site is built with Jekyll and is running on GitHub pages.


#### Running locally

You can use Docker to avoid installing Ruby and/or gems. More instructions
[here](https://github.com/envygeeks/jekyll-docker/blob/master/README.md)

```shell
export JEKYLL_VERSION=3.8.4

# Build the web site
docker run --rm -p4000:4000 --volume="$PWD:/srv/jekyll" -it jekyll/builder:$JEKYLL_VERSION jekyll serve --livereload --config _config.yml,_config_local.yml
```
