# Pokédex Colaborativa — Projeto Final

## Integrantes
• **GABRIEL GUIMARÃES AGUIAR** — matrícula 22504655
• Usuário GitHub: gabrieljs77
• Funcionalidade: todas (trabalho individual, autorizado pelo professor)
• Principal PR: <https://github.com/gabrieljs77/bootcamp2-projeto-final/pull/2>

## Descrição
Pokédex web que consome a **PokéAPI** e permite favoritar Pokémon, salvando favoritos e anotações em um banco **Supabase (PostgreSQL)**. O título da lista mostra a quantidade de favoritos.

## Links
• Repositório: <https://github.com/gabrieljs77/bootcamp2-projeto-final>
• Aplicação (GitHub Pages): <https://gabrieljs77.github.io/bootcamp2-projeto-final/>
• Docker Hub: <https://hub.docker.com/r/gabrielagaguiar/bootcamp2-projeto-final>

## Executar com Docker
```
docker run -d -p 8080:80 gabrielagaguiar/bootcamp2-projeto-final:1.0
```
Abra http://localhost:8080

## Executar localmente
Extraia o projeto e abra o `index.html` no navegador.

## Testes
```
npm install
npm test
```
6 testes automatizados (Jest) rodam no GitHub Actions a cada Pull Request, e o CI também valida o `docker build`.
## Fluxo de trabalho
A `main` é protegida por ruleset: todo código entra por Pull Request e só faz merge com o check `test` verde. Como o trabalho é individual, as aprovações obrigatórias estão em 0, mas PR e CI continuam obrigatórios.

## Pull Requests
• <https://github.com/gabrieljs77/bootcamp2-projeto-final/pull/1> — primeira tentativa de adicionar `textoContador` (a função não entrou)
• <https://github.com/gabrieljs77/bootcamp2-projeto-final/pull/2> — função `textoContador` + teste. **Bloqueado pelo CI** e depois corrigido
• <https://github.com/gabrieljs77/bootcamp2-projeto-final/pull/3> — id no título dos favoritos (`index.html`)
• <https://github.com/gabrieljs77/bootcamp2-projeto-final/pull/4> — contador de favoritos (`script.js`)
• <https://github.com/gabrieljs77/bootcamp2-projeto-final/pull/5> — CI valida o `docker build` (`ci.yml`)
• <https://github.com/gabrieljs77/bootcamp2-projeto-final/pull/6> e <https://github.com/gabrieljs77/bootcamp2-projeto-final/pull/7> — evidências (prints)

## Evidências
• PR #2 bloqueado pelo CI: arquivo `Untitled.png` no repositório
• Imagem no Docker Hub: print no repositório

## Conflitos de merge
Não ocorreu nenhum conflito, pois só houve um colaborador.
