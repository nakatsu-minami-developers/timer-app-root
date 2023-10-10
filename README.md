# timer-appのルートリポジトリ
## Submodules
[front](https://github.com/nakatsu-minami-developers/timer-app-front)

[api](https://github.com/nakatsu-minami-developers/timer-app-api)


# Usage
```
$ git clone --recurse-submodules git@github.com:nakatsu-minami-developers/timer-app-root.git
$ docker-compose build
$ docker-compose run --rm front yarn install
$ docker-compose run --rm api yarn install
$ docker-compose up
```
# Front

## CSS
Tailwind CSS, daisyUI

## Test/Lint
```
# Jest
$ docker-compose run --rm front yarn test

# ESLint
$ docker-compose run --rm front yarn lint

# Prettier
$ docker-compose run --rm front yarn format
```

# Api
