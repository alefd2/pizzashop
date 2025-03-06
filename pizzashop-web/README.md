# Pizzashop Web 🍕

Este é o projeto Pizzashop Web, uma aplicação web para gerenciar pedidos de pizza.

## Tecnologias Utilizadas

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)](https://vitejs.dev/)


## Testes e Plugins

Para garantir a qualidade do código, utilizamos as seguintes ferramentas:

[![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)](https://vitest.dev/) - Framework de testes unitários rápido e moderno, similar ao Jest

[![Testing Library](https://img.shields.io/badge/-TestingLibrary-%23E33332?style=for-the-badge&logo=testing-library&logoColor=white)](https://testing-library.com/) - Biblioteca para testar componentes React de forma mais próxima ao usuário real

[![jest-dom](https://img.shields.io/badge/jest--dom-c21325?style=for-the-badge&logo=jest&logoColor=white)](https://testing-library.com/docs/ecosystem-jest-dom/) - Extensão/plugin da `Testing Library` com matchers personalizados para testar elementos DOM

[![Playwright](https://img.shields.io/badge/Playwright-45ba4b?style=for-the-badge&logo=playwright&logoColor=white)](https://playwright.dev/) - Framework para testes end-to-end (E2E) automatizados

Plugins adicionais:

[![jsdom](https://img.shields.io/badge/jsdom-yellow?style=for-the-badge&logo=javascript&logoColor=black)](https://github.com/jsdom/jsdom) - Implementação do DOM para ambiente Node.js, permitindo testar código browser-like


Para executar os testes:
```bash
# Executa todos os testes unitários
npm run test
# ou
yarn test

# Executa os testes unitários em modo watch
npm run test:watch
# ou
yarn test:watch

# Executa os testes E2E com Playwright
npm run test:e2e
# ou
yarn test:e2e
```

## Como Instalar

1. Clone o repositório:
```bash
git clone https://github.com/alefd2/pizzashop-web.git
cd pizzashop-web
```

2. Instale as dependências:
```bash
npm install
# ou
yarn install
```

3. Execute o projeto localmente:
```bash
npm run dev
# ou
yarn dev
```

## Deploy

Para fazer o build do projeto:
```bash
npm run build
# ou
yarn build
```

O projeto estará disponível na pasta `dist` para deploy.