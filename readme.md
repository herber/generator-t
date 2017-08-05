# generator-t

> A minimalist starting point for node projects

This a fork of [sindresorhus's](https://github.com/sindresorhus) [generator-nm](https://github.com/sindresorhus/generator-nm).


## Install

```
$ npm install --global yo generator-nm
```


## Usage

With [yo](https://github.com/yeoman/yo):

```
$ yo t
```

### Cli options

```
$ yo t --help

  Usage:
    yo t [options]

  Options:
    --help          # Print the generator's options and usage
    --skip-cache    # Do not remember prompt answers                      Default: false
    --skip-install  # Do not automatically install dependencies           Default: false
    --org           # Publish to a GitHub organization account
    --cli           # Add a CLI
    --coverage      # Add code coverage with nyc
    --codecov       # Upload coverage to codecov.io (implies --coverage)
```

The `--org` option takes a string value (i.e. `--org=bytes`). All others are boolean flags and can be negated with the `no` prefix (i.e. `--no-codecov`). You will be prompted for any options not passed on the command-line.


## License

MIT © [tobihrbr](https://tobihrbr.com)

Based on [generator-nm](https://github.com/sindresorhus/generator-nm) by [sindresorhus](https://github.com/sindresorhus). Thanks!
