# NLW Agents

Este projeto foi desenvolvido durante o evento NLW da Rocketseat.

## Tecnologias e Bibliotecas Utilizadas

- **React 19** – Biblioteca principal para construção da interface.
- **Vite** – Bundler e servidor de desenvolvimento rápido.
- **TypeScript** – Tipagem estática para JavaScript.
- **TailwindCSS** – Utilitário para estilização com classes utilitárias.
- **@radix-ui/react-slot** – Composição avançada de componentes.
- **lucide-react** – Ícones SVG para React.
- **react-router-dom** – Roteamento SPA.
- **class-variance-authority, clsx, tailwind-merge** – Utilitários para manipulação de classes CSS.
- **tw-animate-css** – Animações CSS integradas ao Tailwind.
- **@biomejs/biome** – Linter e formatter.
- **@vitejs/plugin-react** – Integração React com Vite.

## Padrões de Projeto

- **Componentização**: Uso extensivo de componentes reutilizáveis.
- **Roteamento SPA**: Implementado com `react-router-dom`.
- **Provider Pattern**: Contextos globais como QueryClientProvider para gerenciamento de dados.
- **Aliases**: Utilização de aliases para importação de módulos (`@/components`, `@/lib`, etc).

## Setup e Configuração

1. **Clone o repositório e instale as dependências:**

   ```bash
   npm install
   ```

2. **Rodando o projeto em modo desenvolvimento:**

   ```bash
   npm run dev
   ```

3. **Build para produção:**

   ```bash
   npm run build
   ```

4. **Preview do build:**

   ```bash
   npm run preview
   ```

5. **Estilização:**

   - O TailwindCSS já está configurado e importado em `src/index.css`.
   - Animações adicionais via `tw-animate-css`.

6. **Linting e formatação:**
   - O projeto utiliza o Biome para linting e formatação automática.

## Estrutura de Pastas

- `src/` – Código-fonte principal.
- `src/components/` – Componentes reutilizáveis.
- `src/pages/` – Páginas da aplicação.
- `src/lib/` – Utilitários e funções auxiliares.

---

Se precisar de mais detalhes ou exemplos de uso, é só pedir!
