# docker-jq

Docker image for [jq](http://stedolan.github.io/jq/) based on [alpine linux](https://alpinelinux.org/) image

## Usage

Test `jq` command:

```bash
$ echo '{"foo":"bar"}' | docker run --rm -i --name jq bolasblack/alpine-jq -C '.'
{
  "foo": "bar"
}
```
