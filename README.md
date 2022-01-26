yjit-extra-benchmarks
==========

This repo contains supplemental benchmarks for yjit-bench that shouldn't normally be run by default. For instance, the Discourse benchmark does a lot of configuration that isn't available on non-Linux systems and isn't always wanted when available.

To use this repository, you should copy any appropriate benchmarks into your main benchmarks directory (perhaps where you cloned yjit-bench?). Both yjit-bench and yjit-metrics will automatically pick up any new benchmarks in the directory.

No benchmarking harness is included in this repo. Instead, use the harness from yjit-bench or yjit-metrics.

## Installation

```
# To copy a benchmark into a new location
cp -r yjit-extra-benchmarks/benchmarks/discourse yjit-bench/benchmarks/
```

## License

See LICENSE.md

## Contributing

See CONTRIBUTING.md. You may also be interested in the yjit-bench or yjit-metrics repositories.

