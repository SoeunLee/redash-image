# redash-image
official docker images for offline environment

## contents
`redash.tar` redash/redash
`postgres.tar` postgres:9.5-alpine
`redis.tar` redis:3-alpine
`maildev.tar` djfarrelly/maildev

## docker images
REPOSITORY           TAG          IMAGE ID       CREATED         SIZE
postgres             9.5-alpine   f6e71ff7ed6b   22 months ago   36.2MB
redash/redash        latest       1b48a51810b5   3 years ago     1.31GB
djfarrelly/maildev   latest       8c016b0ceb3c   3 years ago     79.8MB
redis                3-alpine     6e94a98d3442   4 years ago     22.9MB

## how to load
```docker load < redash.tar```
