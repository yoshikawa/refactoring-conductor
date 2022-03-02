![Go test/lint](https://github.com/st-tech/refactoring-conductor/workflows/Go%20test/lint/badge.svg)

# Refactoring Conductor

Refactoring Conductor is a CLI tool written in Go for performing static analysis.
Focusing on visualising complexity of code, using [Cognitive Complexity](https://docs.codeclimate.com/docs/cognitive-complexity) as indicator value.

## Usage

### Single File Analysis

```sh
$ go run main.go single path/to/file.vbs
```

### Multi File Analysis

```
$ go run main.go directory path/to/directory/
```

### Other usages

To see all the usages use help command.

```sh
$ go run main.go --help
```

## Testing

To run test

```sh
$ go test -v ./test
```

## Note

Currently, this tool only works with VBScript/VB.Net and only supports **if-statement**. Other operators and languages are working in progress.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/st-tech/refactoring-conductor. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Code of Conduct

Everyone interacting in this project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](./CODE_OF_CONDUCT.md).

## License

Copyright &copy; ZOZO Technologies, Inc. Originally created by [Taiki Yoshikawa](http://github.com/yoshikawa).  
Released under the [Apache License 2.0](./LICENSE)
