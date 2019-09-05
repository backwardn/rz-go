<p align="center">
  <h3 align="center">rz</h3>
  <p align="center">RipZap - The fastest structured, leveled JSON logger for Go ⚡️. Dependency free.</p>
</p>

--------

[Make logging great again](https://kerkour.com/post/logging/)

[![GoDoc](https://godoc.org/gitlab.com/z0mbie42/rz-go?status.svg)](https://godoc.org/gitlab.com/z0mbie42/rz-go)
[![GitHub release](https://img.shields.io/github/release/z0mbie42/rz-go.svg)](https://github.com/z0mbie42/rz-go/releases)
<!-- [![Coverage](http://gocover.io/_badge/github.com/z0mbie42/rz-go)](http://gocover.io/github.com/z0mbie42/rz-go) -->

![Console logging](docs/example_screenshot.png)

The rz package provides a fast and simple logger dedicated to JSON output avoiding allocations and reflection..

Uber's [zap](https://godoc.org/go.uber.org/zap) and rs's [zerolog](https://godoc.org/github.com/rs/zerolog)
libraries pioneered this approach.

ripzap is an update of zerolog taking this concept to the next level with a **simpler** to use and **safer**
API and even better [performance](#benchmarks).

To keep the code base and the API simple, ripzap focuses on efficient structured logging only.
Pretty logging on the console is made possible using the provided (but inefficient)
[`Formatter`s](https://godoc.org/github.com/z0mbie42/rz-go#LogFormatter).


## Moved to https://gitlab.com/z0mbie42/rz-go
