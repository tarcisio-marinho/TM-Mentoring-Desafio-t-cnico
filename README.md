# Instruções para o Projeto de Monitoramento de Preços

Este documento contém as diretrizes e requisitos para o desenvolvimento de uma ferramenta de monitoramento de preços com web scraping e interface de usuário. O projeto deve ser desenvolvido utilizando a linguagem C# e seguir as especificações listadas abaixo.

## Requisitos Técnicos

### Ambiente de Desenvolvimento

- *Linguagem:* C#
- *Framework:* Utilizar .NET Core, .NET 5 ou .NET 6.
- *Web Scraping:* Escolher entre Html Agility Pack e AngleSharp para a extração de dados.
- *Banco de Dados:* Você decide qual banco de dados vai utilizar.
- *Interface de Usuário:* A tecnologia para desenvolvimento da interface é de escolha do entrevistado.

### Funcionalidades

#### Extração de Dados

- Desenvolver uma funcionalidade que extraia periodicamente informações de produtos de uma página de e-commerce: nome, preço, avaliação média dos usuários e URL do produto.

#### Armazenamento de Dados

- Os dados extraídos devem ser armazenados em um banco de dados, incluindo um histórico de preços.

#### Atualização Periódica

- Implementar a re-execução automática do processo de web scraping em intervalos regulares.

### Interface de Usuário

- Desenvolver uma interface que permita aos usuários visualizar os produtos e os seus preços.

## Orientações Gerais

- Priorize a clareza e manutenibilidade do código.
- Documente adequadamente todas as funcionalidades implementadas.
- Utilize padrões de design e boas práticas de programação.

## Entrega do Projeto

- O projeto deve ser entregue em um repositório Git, contendo o código fonte, arquivos de configuração necessários e uma documentação detalhada do projeto.
- Inclua um arquivo README.md com uma visão geral do projeto, instruções de instalação e uso, e uma descrição das tecnologias e técnicas utilizadas.

## Avaliação

O projeto será avaliado com base em:

- Funcionalidade: Todas as funcionalidades requisitadas devem estar implementadas e funcionando corretamente.
- Qualidade do Código: Organização, legibilidade e aderência a boas práticas.
- Documentação: Clareza e completude tanto no código quanto na documentação fornecida.
- Inovação e Uso da Tecnologia: Eficiência na escolha e uso das tecnologias e na solução de problemas.

Boa sorte e estamos ansiosos para ver sua solução!
