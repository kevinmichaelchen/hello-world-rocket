# hello-world-rocket

[![Build Status](https://travis-ci.org/kevinmichaelchen/hello-world-rocket.svg?branch=master)](https://travis-ci.org/kevinmichaelchen/hello-world-rocket)

A simple webserver built with Rust and Rocket.

## Getting started
```
# Download rustup
curl https://sh.rustup.rs -sSf | sh

# Get the latest nightly version of Rust (required by Rocket)
rustup default nightly
rustup update && cargo update

cargo run

curl http://localhost:8000/hello/John/58
```
