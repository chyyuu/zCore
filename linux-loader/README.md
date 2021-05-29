## run
```
$ cargo run -- /bin/busybox
```

## debug
To debug, set `RUST_LOG` environment variable to one of `error`, `warn`, `info`, `debug`, `trace`.

```
$ RUST_LOG=info cargo run  -- /bin/busybox
```
