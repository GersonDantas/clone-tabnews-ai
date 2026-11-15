# Contexto do projeto

O **clone-tabnews-ai** tem como objetivo implementar o TabNews para acompanhar o curso.dev, utilizando agentes de IA.

## Estado atual

- A aplicação exibe uma página simples da Família Dantas, com uma lista de nomes.
- Usa Next.js 16 (Active LTS), React, App Router, JavaScript e CSS.
- `app/layout.js` define o idioma, o título e importa o CSS global.
- `app/page.js` contém a página inicial; `app/globals.css` contém os estilos.
- As funcionalidades do TabNews ainda não foram implementadas.

## Orientações

- Mantenha a implementação simples e siga as convenções do Next.js.
- Consulte os arquivos existentes antes de assumir que uma funcionalidade já existe.
- Use `npm run dev` para desenvolvimento e `npm run build` para validar a compilação de produção.
- Atualize este contexto conforme o projeto evoluir.

<!-- BEGIN:nextjs-agent-rules -->

## This is NOT the Next.js you know

This version has breaking changes — APIs, conventions, and file structure may all differ from your training data. Read the relevant guide in `node_modules/next/dist/docs/` (resolved from this file's directory; in monorepos the `next` package may not be visible from the repo root) before writing any code. Heed deprecation notices.

This block is written and re-added by `next dev` — verify at `node_modules/next/dist/server/lib/generate-agent-files.js`. Removing it from a diff only re-creates the uncommitted change; committing it with your work keeps the tree clean.

<!-- END:nextjs-agent-rules -->
