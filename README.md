[![Build Status](https://travis-ci.com/RENCI/pdspi-example.svg?branch=master)](https://travis-ci.com/RENCI/pdspi-example)

# pdspi-plugin-example

### What does this plug-in do?

An example pluging.

### build docker image

```
docker build . -t <image>
```

### run docker image

example `docker-compose.yml`

`PDS_PORT`: pds backend port

`PDS_HOST`: pds backend host

`PDS_VERSION`: pds backend version

### run test

```
test/test.sh
```

