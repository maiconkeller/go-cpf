# cpfer

[CPF] validator and generator written in Go.

## Usage

#### Command-line example:
```bash
$ cpfer
487.160.523-07
$ cpfer 487.160.523-07
✔
```

To generate, just run it without any arguments.

#### API example:
```go
package main

import "github.com/mvrilo/cpfer/lib"

func main() {
        println(cpf.GeneratePretty())
}
```

## License

See [LICENSE](https://github.com/mvrilo/cpfer/blob/master/LICENSE)

[CPF]: https://en.wikipedia.org/wiki/Cadastro_de_Pessoas_F%C3%ADsicas
