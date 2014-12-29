# go-cpf

[CPF](https://en.wikipedia.org/wiki/Cadastro_de_Pessoas_F%C3%ADsicas) validator and generator written in Go.

## Usage

#### Command-line example:
```bash
$ go get github.com/mvrilo/go-cpf/cmd/cpf
$ cpf
487.160.523-07
$ cpf 487.160.523-07
✔
```

To generate, just run it without any arguments.

#### API example:
```go
package main

import "github.com/mvrilo/go-cpf"

func main() {
        println(cpf.GeneratePretty())
}
```

## License

See [LICENSE](https://github.com/mvrilo/go-cpf/blob/master/LICENSE)
