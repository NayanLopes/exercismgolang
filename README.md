# Exercícios GoLang

Bem-vindo ao meu repositório de exercícios em GoLang!

Este é um espaço dedicado para a prática e aprendizado da linguagem de programação Go (ou Golang). Aqui você encontrará soluções para diversos desafios e exercícios, com o objetivo de aprimorar minhas habilidades e compreensão da linguagem.

---

## Estrutura do Repositório

Cada conjunto de exercícios ou problema resolvido geralmente estará em seu próprio diretório, seguindo uma estrutura lógica para fácil navegação. Por exemplo:
---
```
.
├── exercicio_01_nome_do_desafio/
│   ├── main.go
│   └── README.md (opcional: com detalhes específicos do exercício)
├── exercicio_02_outro_desafio/
│   ├── main.go
│   └── test_exercicio.go (se houver testes unitários)
└── README.md (este arquivo)
```
## Como Rodar os Exercícios

Para rodar qualquer exercício específico, navegue até o diretório correspondente e execute o comando Go:

1.  **Navegue até a pasta do exercício:**
    ```bash
    cd nome_do_exercicio/
    ```
2.  **Execute o arquivo Go:**
    ```bash
    go run main.go
    ```
    (Ou o nome do arquivo `.go` principal, caso seja diferente de `main.go`)

Se houver testes, você pode rodá-los com:

```bash
go test ./...
