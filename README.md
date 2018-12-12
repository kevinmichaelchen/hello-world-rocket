# hello-world-rocket

[![Build Status](https://travis-ci.org/kevinmichaelchen/hello-world-rocket.svg?branch=master)](https://travis-ci.org/kevinmichaelchen/hello-world-rocket)

This project is a simple webserver built with [Rust](https://www.rust-lang.org)
and [Rocket](https://rocket.rs).
It comes with a simple unit test and TravisCI integration.

## Setting up the environment
To setup your environment for the first, run
```bash
make setup
```
This will download the nightly builds of Rust and its package manager, [cargo](https://doc.rust-lang.org/cargo/).

## Running the server
```bash
# Start the server!
make

# Hit an endpoint!
curl http://localhost:8000/hello/John/58
```

## Running tests
```bash
make test
```

