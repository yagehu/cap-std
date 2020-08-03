<div align="center">
  <h1><code>cap-tempdir</code></h1>

  <p>
    <strong>Capability-oriented temporary directories</strong>
  </p>

  <p>
    <a href="https://github.com/sunfishcode/cap-std/actions?query=workflow%3ACI"><img src="https://github.com/sunfishcode/cap-std/workflows/CI/badge.svg" alt="Github Actions CI Status" /></a>
    <a href="https://cirrus-ci.com/github/sunfishcode/cap-std"><img src="https://api.cirrus-ci.com/github/sunfishcode/cap-std.svg" alt="Cirrus CI Status" /></a>
  </p>
</div>

`cap-tempfile` crate provides utilities for creating temporary directories
via the [`tempfile`] crate, but which provide [`Dir`]s instead of `Path`s.

[`tempfile`]: https://crates.io/crates/tempfile
[`Dir`]: https://docs.rs/cap-std/latest/cap_std/fs/struct.Dir.html