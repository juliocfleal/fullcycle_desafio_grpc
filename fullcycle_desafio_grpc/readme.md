# Desafio gRPC

Este projeto foi criado para o desafio da semana fullstack & fullcycle

## Como executar:

**Passo 1:** Faça o clone do projeto no diretório de sua preferência.

```shell
git clone github.com/juliocfleal/fullcycle_desafio_grpc
```

**Passo 2:** Vá para o terminal, acesse o diretório que você clonou o projeto e execute o comando abaixo:

```shell
go run cmd/main.go
```

**Passo 3:** Abra outra tela do terminal, acesse o diretório que você clonou o projeto e execute o comando abaixo:

```shell
evans -r repl
```

**Passo 4:** Já no evans digite o comando abaixo para selecionar o pacote

```shell
package github.com.codeedu.codepix
```

**Passo 5:** Com o pacote selecionado digite o comando abaixo para selecionar o service

```shell
service ProductService
```

**Passo 6:** Para criar um novo produto digite o comando abaixo

```shell
call CreateProduct
```

Preencha os campos solicitados

**Passo 7:** Para consultar os produtos criados, digite o comando abaixo

```shell
call FindProducts
```