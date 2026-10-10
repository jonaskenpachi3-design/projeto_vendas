# Site de Venda de Produtos

Página de vendas feita com **HTML e CSS**, com uma base de back-end em **Spring Boot** para evolução futura. Projeto da disciplina do Web Academy (UFAC), desenvolvido com issues e commits referenciados.

## Funcionalidades atuais

- Página inicial com mensagem de boas-vindas.
- Lista de produtos à venda (notebook, mouse, fone e cabo HDMI).
- Back-end Spring Boot criado a partir do Spring Initializr, ainda sem endpoints.

## Tecnologias

| Parte | Tecnologias |
| --- | --- |
| Front-end | HTML5, CSS3 |
| Back-end | Java 25, Spring Boot 4.1, Maven (Maven Wrapper incluído) |

## Estrutura

```text
projeto_vendas/
├── index.html               # Página inicial
├── bluestyle.css            # Estilos
├── back-end/
│   └── webacademy/          # Projeto Spring Boot (Maven)
├── LICENSE
└── README.md
```

## Como executar

### Front-end

Abra o arquivo `index.html` no navegador. Não há dependências para instalar.

### Back-end (opcional)

Requer JDK 25 instalado.

```bash
cd back-end/webacademy
./mvnw spring-boot:run
```

No Windows, use `mvnw.cmd spring-boot:run`.

## Próximos passos

- Criar a entidade de produtos e os endpoints da API no back-end.
- Integrar a página com a API para listar os produtos.

## Autor e licença

Desenvolvido por **Jonas Sousa**. Distribuído sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE).
