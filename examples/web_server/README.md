Static file handler example
===========================

To try this example, you need GNU `make`, `git` and
[relx](https://github.com/erlware/relx) in your PATH.

To build the example, run the following command:

``` bash
$ make
```

To start the release in the foreground:

``` bash
$ ./_rel/bin/web_server_example console
```

Then point your browser at [http://localhost:8080](http://localhost:8080)
to browse the contents of the `priv` directory.
