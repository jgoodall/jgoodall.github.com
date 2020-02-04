
To test locally:

```
export JEKYLL_VERSION=3.8
docker run --rm \
  -p=4000:4000 \
  --volume="$PWD:/srv/jekyll" \
  --volume="$PWD/vendor/bundle:/usr/local/bundle" \
  jekyll/jekyll:$JEKYLL_VERSION \
  jekyll serve
```