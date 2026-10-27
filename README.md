# Quillo examples

Small programs, each showing one part of [Quillo](https://github.com/quillolang/quillo).
Every one is a whole program: run it and open <http://localhost:8080>.

```sh
git clone https://github.com/quillolang/examples.git quillo-examples
cd quillo-examples
quillo run notes.qwe --watch
```

(`quillo` comes from [Getting started](https://github.com/quillolang/quillo#getting-started).)
They are also on [quillolang.org/docs/examples](https://quillolang.org/docs/examples/),
each with its whole source.

| Example | What it shows |
|---|---|
| [`hello.qwe`](hello.qwe) | Routes: path parameters, typed query patterns |
| [`orders.qwe`](orders.qwe) | Payload-based routing and middleware |
| [`todo.qwe`](todo.qwe) | A server-rendered app with a JSON API |
| [`notes.qwe`](notes.qwe) | SQLite and a live component |
| [`scroll.qwe`](scroll.qwe) | Infinite scroll over 100,000 rows, rendering only a window |
| [`virtual.qwe`](virtual.qwe) | A virtual list of a million rows |
| [`compose.qwe`](compose.qwe) | Views and components built from each other |
| [`layout.qwe`](layout.qwe) | A page described as JSON, with a live editor |
| [`spa.qwe`](spa.qwe) | A single-page app: client-side navigation, deep links, 404s |
| [`life.qwe`](life.qwe) | Conway's Game of Life, run by a timer in the browser |
| [`storm.qwe`](storm.qwe) | A dashboard under a storm of random changes |
| [`telemetry.qwe`](telemetry.qwe) | UDP readings shown live; [`sensors.qwe`](sensors.qwe) sends them |
| [`media.qwe`](media.qwe) | A camera's RTP stream in the page |
| [`rust.qwe`](rust.qwe) | Rust in a program, from [`rust.qwer`](rust.qwer) |
| [`services/`](services) | A shop that bills through a billing service, in one process or split apart |
| [`index.qwe`](index.qwe) | All of them mounted in one server, behind tabs |

CI runs `quillo check` on every example against quillo's `main`.

## License

MIT
