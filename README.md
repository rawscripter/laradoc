# LARADOC

Make your life easier with laradoc.

## Install Laravel

laravel files will go inside src folder

```composer
create-project --prefer-dist laravel/laravel .
```

# Build docker images and run the applications

```docker
docker-compose build
docker-compose up -d
```

And you are ready to build something amazing :) Localhost url: [http://localhost:8090](http://localhost:8090)

## To run composer commands

```docker
docker-compose run --rm composer ....
```

## To run artisan commands

```docker
docker-compose run --rm artisan ....
```

## To run npm commands

```docker
docker-compose run --rm npm ....
```

## License

[MIT](https://choosealicense.com/licenses/mit/)

```

```
