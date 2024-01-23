## Dependencies

In order to build using the provided [Makefile](Makefile), you should install the following tools:
  - [goreleaser](https://goreleaser.com/)
  - [gocover-cobertura](https://github.com/t-yuki/gocover-cobertura)

  You should also install [garble](https://github.com/burrowers/garble) and put the provided [garble-custom](garble-custom) script somewhere included in you `PATH` environmental variable in order to be able to build this obfuscated version of `chisel`.

#### GoReleaser

Setup instructions can be found at the [official documentation](https://goreleaser.com/install/#nur).

#### gocover-cobertura

Run the following outside the project directory (*e.g.*, at your home directory).

```
go get golang.org/x/tools/cmd/cover
go install github.com/t-yuki/gocover-cobertura@latest
```

#### garble

Run:
```
go install mvdan.cc/garble@latest
```
