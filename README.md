# Projeto de WebScrapping de composição de alimentos

Este documento contém as diretrizes e requisitos para o desenvolvimento de uma ferramenta de monitoramento de preços com web scraping e interface de usuário. O projeto deve ser desenvolvido utilizando a linguagem C# e seguir as especificações listadas abaixo.
- Link: https://www.tbca.net.br/base-dados/composicao_estatistica.php?pagina=1&atuald=1#

## Requisitos Técnicos

### Ambiente de Desenvolvimento

- *Linguagem:* C#
- *Framework:* Utilizar .NET Core, .NET 5 ou .NET 6.
- *Web Scraping:* Escolher entre Html Agility Pack e AngleSharp para a extração de dados.
- *Banco de Dados:* Você decide qual banco de dados vai utilizar.
- *Interface de Usuário:* A tecnologia para desenvolvimento da interface é de escolha do entrevistado.

### Funcionalidades

#### Extração de Dados

- Desenvolver uma funcionalidade que extraia informações de alimentos: Código, Nome, Nome Cientifico, Grupo, e todos os Componentes:

<img width="282" alt="image" src="https://github.com/tarcisio-marinho/TM-Mentoring-Desafio-tecnico/assets/21285247/479f7a5e-5e0d-4088-bb39-b96474739ff4">


#### Armazenamento de Dados

- Os dados extraídos devem ser armazenados em um banco de dados. A escolha do banco de dados e a estrutura de tabelas ou arquivos, fica por sua parte.

### Interface de Usuário

- Desenvolver uma interface que permita aos usuários visualizar os alimentos e suas composições.
- Busca por nome do alimento

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
