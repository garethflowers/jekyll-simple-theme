# Contributing

## Serve using Docker

Run the following in a terminal:
```sh
docker run \
	--rm \
	--volume="$PWD:/srv/jekyll" \
	--interactive \
	--tty \
	--publish 4000:4000 \
	jekyll/jekyll \
	jekyll serve
```
