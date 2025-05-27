# Pocketdex

Pokédex online desenvolvida em Angular, usando a PokéAPI para exibir informações da primeira geração de Pokémon. 

O projeto serve como um exemplo prático de integração com APIs públicas, componentização e uso de Angular para criar SPAs (Single Page Applications) interativas e responsivas.

## Funcionalidades

- Lista dos 151 primeiros Pokémon da franquia.
- Busca por nome em tempo real.
- Exibição dos tipos e imagens de cada Pokémon.
- Cores de fundo dinâmicas de acordo com o tipo do Pokémon.
- Consumo direto da [PokéAPI](https://pokeapi.co/).

## Estrutura e Destaques do Código

- **Angular:** Arquitetura baseada em módulos, componentes e serviços.
- **src/app/service/poke-api.service.ts:** Serviço centralizado que consulta a PokéAPI, buscando todos os Pokémon e os detalhes de cada um.
- **src/app/shared/poke-list/poke-list.component.ts + .html:** Componente responsável por exibir a lista com filtro de busca e renderização dinâmica dos dados.
- **src/app/shared/poke-search/poke-search.component.ts:** Componente de input para busca de Pokémon.
- **src/app/pages/home/home.component.html:** Monta a página principal com cabeçalho e lista.
- **src/main.ts / src/index.html:** Bootstrapping da aplicação Angular.

> ⚠️ Estes arquivos são apenas parte do projeto. Para ver mais, confira o [código completo no GitHub](https://github.com/hisirdox/pocketdex/search?q=main+app+index+script).

## Exemplos de Uso e Aplicação

Pocketdex pode ser útil em:
- Demonstração de consumo de API REST em Angular.
- Projetos de estudo de arquitetura de SPA.
- Ferramenta rápida para consulta de Pokémon da primeira geração.
- Base para projetos de catálogo (filmes, jogos, personagens) usando outras APIs.

## Como rodar

1. Clone o repositório:
   ```bash
   git clone https://github.com/hisirdox/pocketdex.git
   cd pocketdex
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Rode o projeto:
   ```bash
   ng serve
   ```
4. Acesse em [http://localhost:4200](http://localhost:4200).

---

Desenvolvido por [hisirdox](https://github.com/hisirdox).
