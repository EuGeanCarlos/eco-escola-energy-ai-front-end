# EcoEscola — frontend

Estrutura React/Vite de dashboard. App.jsx importa Sidebar, Header, Dashboard e styles/global.css, mas esses arquivos não estão versionados: o build está bloqueado até recuperar a implementação original.

## Tecnologias

- React 19
- Vite 7
- JavaScript
- ESLint

## Funcionalidades e utilização

A instalação usa npm ci em ecoescola-frontend/. npm run build permite reproduzir o bloqueio; não foi criada uma interface substituta.

## Como executar

```bash
git clone https://github.com/EuGeanCarlos/eco-escola-energy-ai-front-end.git
cd eco-escola-energy-ai-front-end
cd ecoescola-frontend
npm ci
npm run dev
```

Use Node.js 22.12 ou superior e o lockfile versionado. Para compilar, execute npm run build. Limitações descritas acima podem impedir o build.

## Demonstração e publicação

Execução local. Nenhuma demonstração nova foi confirmada nesta etapa.

## Estrutura versionada

```text
README.md
ecoescola-frontend/.gitignore
ecoescola-frontend/README.md
ecoescola-frontend/eslint.config.js
ecoescola-frontend/index.html
ecoescola-frontend/package-lock.json
ecoescola-frontend/package.json
ecoescola-frontend/public/vite.svg
ecoescola-frontend/src/App.css
ecoescola-frontend/src/App.jsx
ecoescola-frontend/src/assets/react.svg
ecoescola-frontend/src/index.css
ecoescola-frontend/src/main.jsx
ecoescola-frontend/vite.config.js
```

## Status

Protótipo / projeto de estudo em desenvolvimento. A descrição acima distingue o que está implementado das dependências ou etapas pendentes.

## Autor e créditos

**Gean Carlos** — estudante de Engenharia de Computação, UEMA.

[GitHub](https://github.com/EuGeanCarlos)

Licenças, autoria compartilhada e atribuições existentes no código e nos materiais originais permanecem aplicáveis.

## Validação desta auditoria — 14/10/2026

Sem publicação nova confirmada. npm ci aprovado; npm run build falhou por ausência de src/components/Sidebar e outros imports originais. Recuperar os componentes originais; não foi criada aplicação substituta.
