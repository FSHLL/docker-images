# Placetopay - Docker Vapor PHP

Custom docker images with [Newrelic](https://newrelic.com/) for php 7.4 and php 8.

## Getting Started 

These instructions will give you some containers on your local machine available to publish on docker hub.

### Build and/or Publish

[build.sh](build.sh) is a script with docker commands to make the process easier.

To build an image (you can change 74 by 80 for php 8):

```
./build.sh php74
```

To build and publish an image:

```
./build.sh php74 -p
```

__Note:__ You need to be logged in docker hub to publish with `docker login` in the placetopay account.

## Resources

- Laravel Vapor Dockerfiles - https://github.com/laravel/vapor-dockerfiles.
- Integrate Newrelic in Laravel Vapor - https://dev.to/davidv99/integrate-newrelic-in-laravel-vapor-4o13.