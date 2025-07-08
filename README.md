# NLW Agents

Este projeto foi desenvolvido durante o evento NLW da Rocketseat. Ele utiliza React, TypeScript e Vite para criar uma aplicação moderna e performática.

## Tecnologias Utilizadas

- **React**: Biblioteca para construção de interfaces de usuário.
- **TypeScript**: Superset do JavaScript que adiciona tipagem estática.
- **Vite**: Ferramenta de build rápida para desenvolvimento web.
- **React Router**: Gerenciamento de rotas na aplicação.
- **React Query**: Gerenciamento de estado assíncrono.
- **TailwindCSS**: Framework CSS utilitário para estilização.
- **Class Variance Authority (CVA)**: Gerenciamento de variantes de classes CSS.
- **Lucide Icons**: Biblioteca de ícones SVG.

## Padrões de Projeto

- **Componentização**: Componentes reutilizáveis e bem definidos.
- **Aliases**: Utilização de aliases para facilitar importações (`@/components`, `@/lib`, etc.).
- **Estrutura Modular**: Separação de responsabilidades em pastas como `pages`, `components`, e `lib`.

## Setup do Projeto

1. **Clone o repositório**:

   ```bash
   git clone <url-do-repositorio>
   cd web
   ```

2. **Instale as dependências**:

   ```bash
   npm install
   ```

3. **Inicie o servidor de desenvolvimento**:

   ```bash
   npm run dev
   ```

4. **Acesse a aplicação**:
   Abra o navegador e acesse [http://localhost:5173](http://localhost:5173).

## Scripts Disponíveis

- `npm run dev`: Inicia o servidor de desenvolvimento.
- `npm run build`: Realiza o build da aplicação para produção.
- `npm run preview`: Visualiza o build de produção.
- `npm run lint`: Executa o linter para verificar problemas no código.

## Configuração Adicional

- **TailwindCSS**: Configurado com suporte a variantes e temas customizados.
- **TypeScript**: Configuração estrita para garantir qualidade no código.
- **ESLint**: Configurado com regras para React, TypeScript e melhores práticas.

## Estrutura de Pastas

- `src/components`: Componentes reutilizáveis da aplicação.
- `src/pages`: Páginas principais da aplicação.
- `src/lib`: Funções utilitárias e configurações globais.
- `src/index.css`: Estilização global com TailwindCSS.

## Requisitos

- **Node.js**: Versão 22.17.0 (definido em `.tool-versions`).
- **Gerenciador de Pacotes**: npm ou equivalente.

---

Desenvolvido com 💜 pela comunidade Rocketseat durante o evento NLW.
