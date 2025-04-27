# Portal TI no Canadá

O [Portal TI no Canadá](https://ti-no-canada.github.io/portal/) é o site oficial da comunidade TI no Canadá no Telegram, servindo como um centro de recursos, atualizações e informações. Contribuições são bem-vindas através de **Pull Requests**.

## Como Contribuir

### Configuração do Ambiente de Desenvolvimento Local

1. Clone o repositório com submódulos:
  ```bash
  git clone --recurse-submodules https://github.com/ti-no-canada/portal.git
  ```

2. Navegue até o diretório do projeto:
  ```bash
  cd portal
  ```

3. Construa e inicie o ambiente de desenvolvimento usando Docker:
  ```bash
  docker-compose up --build -d
  ```

4. Acesse o site localmente em `http://localhost:4000`.

Sinta-se à vontade para contribuir e ajudar a melhorar esta plataforma!

## Sobre o Template Jekyll

Este projeto utiliza o tema [Just the Docs] para Jekyll, que oferece suporte para:

- Implantação no GitHub Pages via Actions
- Builds e previews locais
- Fácil personalização e suporte a plugins

## Licenciamento

Este repositório está licenciado sob a [Licença MIT]. Sinta-se à vontade para reutilizar ou estender o código, e nos avise como podemos melhorá-lo!

[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate
[Licença MIT]: https://pt.wikipedia.org/wiki/Licen%C3%A7a_MIT
