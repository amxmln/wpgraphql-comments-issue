> Quick example to reproduce the `wp-graphql` issue with commenter names.

## Run

- Ensure mysql server is running with `brew services run mysql` (on macOS)
- Run `composer install` to get all plugins and relevant files
- Use `wp server` to run locally (with WP CLI installed)

## Shutdown

- `brew services stop mysql` (macOS)
- Stop server
