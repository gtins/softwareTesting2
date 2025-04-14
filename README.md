# Testes Unitários em C# - Sistema de Livraria

Este repositório é uma continuação do projeto de **testes unitários em C#**, com um foco no domínio de **livraria**. A aplicação permite o cadastro de livros, garantindo que os dados obrigatórios sejam validados corretamente.

## Funcionalidades Implementadas

### Cadastro de Livro
- Um novo livro deve ter obrigatoriamente:
  - Título
  - Autor
  - Ano de publicação
  - Número ISBN
  - Número de páginas

### Validações
- Validação de **título** (não pode ser vazio ou nulo).
- Validação de **páginas** (não pode ser menor ou igual a zero).

## Testes Implementados

- **Testes de Criação de Objeto**: Verificação da criação correta do objeto **Livro**.
- **Testes de Validação**: 
  - Teste de título inválido (vazio ou nulo).
  - Teste de número de páginas inválido (menor ou igual a zero).

### Framework de Testes
- **xUnit**: Framework de testes utilizado.
- **ExpectedObjects**: Biblioteca para comparar objetos de maneira mais simples.

