## About
Attempt to write a basic stathat counter style data using Erlang + Redis

We chose Erlang for its concurrency (and to learn) and Redis for operations it supports like INCR etc.,

## Setup
### Running the server
    wget -c -O erlang.mk https://raw.github.com/extend/erlang.mk/master/erlang.mk
    make
    ./_rel/bin/stat_count console
    # now access http://localhost:8080

### Other References
Creating the base application - http://ninenines.eu/docs/en/cowboy/HEAD/guide/getting_started/
