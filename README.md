# HelloPhoenix

To start your Phoenix app:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.create && mix ecto.migrate`
    * Start postgresql now: $ pg_ctl -D /usr/local/var/postgres start
    * To access the Postgres CLI: $ psql postgres
    * Create a Postgres user and password: postgres=# create role
      hello_phoenix with SUPERUSER LOGIN PASSWORD 'hello_phoenix';
    * To exit the Postgres CLI: postgres=# \q
  * Install Node.js dependencies with `npm install`
  * Start Phoenix endpoint with `mix phoenix.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](http://www.phoenixframework.org/docs/deployment).

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: http://phoenixframework.org/docs/overview
  * Docs: https://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix
