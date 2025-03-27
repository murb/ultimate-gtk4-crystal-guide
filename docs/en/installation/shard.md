# Shard

Bindings are being generated on the fly. This means that there's an additional step after installing the shard that generates the bindings.

- Add the dependency to your `shard.yml`:

```yaml
dependencies:
  gtk4:
    github: hugopl/gtk4.cr
```

If you don't have the `shard.yml` yet, you can start a new crystal project using and then make aforementioned change:

```
$ crystal init app gtktest
```

- Run
```
$ shards install
```

- Run
```
$ ./bin/gi-crystal
```
