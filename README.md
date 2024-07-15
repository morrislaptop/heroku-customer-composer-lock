# Heroku Customer Composer Lock

Set `CUSTOM_COMPOSER_LOCK` to the path of the `composer.lock` file to be used for installing.

Useful for installing additional dependencies per environment.

If using a monorepo, include after any buildpacks like https://github.com/jan-tee/heroku-buildpack-monorepo and before heroku/php.
