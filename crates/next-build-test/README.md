# next-build-test

This binary lets you sidestep all of the node bundling and run a turbo build
against a raw rust binary. It does _not_ do everything nextjs does, but it
is an ok approximation.

## Getting started

You will need a project_options file that points to some nextjs repo that has
its dependencies installed. Run the binary with the `generate` command to
build one, then tweak it manually if needed.

```sh
cargo run -- generate /path/to/project > project_options.json
cargo run -- run
```

## Flags

The `run` command supports 4 flags:

- `strategy` can be one of sequential, concurrent, or parallel. defines how
  work is structured
- `factor` defines how many pages should be built at once. defaults to num_cpus
- `limit` defines the highest number of pages to build. the pages are
  shuffled deterministically. defaults to 1 page
- `pages` a comma separated list of routes to run. queues that precise set in
  the order specified
