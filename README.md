# heroku-buildpack-multi

Use multiple buildpacks on your app

## Usage

    $ heroku config:add BUILDPACK_URL=https://github.com/jemmanuel/heroku-buildpack-multi

    $ cat .buildpacks
    https://github.com/winglian/heroku-buildpack-php.git#mpm-event-php55-fpm
	https://github.com/heroku/heroku-buildpack-ruby.git

## Changes made
	chmod-ed ./vendor/bin directory