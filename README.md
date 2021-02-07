# Example application: Rust, Warp & Heroku

[![Build Status](https://travis-ci.org/qalens/rust-buildpack-example-warp.svg?branch=master)](https://travis-ci.org/qalens/rust-buildpack-example-warp)

[Rust][] is a language suitable for high-peformance, reliable web services. [Warp][] is a popular Rust web framework. [Heroku][] deploys, manages and scales web applications.

[Rust]: https://www.rust-lang.org/
[Warp]: https://docs.rs/warp
[Heroku]: https://www.heroku.com/

To deploy this application to Heroku, use this button:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

Or, if you'd prefer to use the command line, try running:

``` sh
git clone https://github.com/qalens/rust-buildpack-example-warp.git
cd rust-buildpack-example-warp
heroku create --buildpack emk/rust
git push heroku master
```

This should make a local copy of this application and deploy it to Heroku.

For further instructions, see the [page for this buildpack][buildpack].

[buildpack]: https://github.com/emk/heroku-buildpack-rust

## Does this work with the latest version of Rust?

This application works with version 1.49 of Rust, which theoretically means
that it should run on any future 1.x release of Rust. If it doesn't work,
please file a bug.