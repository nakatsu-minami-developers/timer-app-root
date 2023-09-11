# This vue project is started using vite

# CSS
Tailwind CSS, daisyUI

# Usage
```
$ git clone git@github.com:shota-nagato/vue3-docker.git
$ docker-compose build
$ docker-compose run --rm front yarn install
$ docker-compose up
```

# Test/Lint
```
# Jest
$ docker-compose run --rm front yarn test

# ESLint
$ docker-compose run --rm front yarn lint

# Prettier
$ docker-compose run --rm front yarn format
```