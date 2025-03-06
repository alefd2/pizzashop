# Pizza Shop Project
This project consists of two main parts:

## 📱 Web Application (`/web`)
A React-based web interface for pizza shop management.

## 🚀 API (`/api`) 
A backend REST API that serves the web application.

### Getting Started

1. Enter each directory separately
2. Follow the setup instructions in their respective README files

```bash
# For the web application
cd web

# For the API
cd api
```

### 🔧 Technologies Used

### Web Application
- React.js with TypeScript
- Tailwind CSS for styling
- React Router DOM for navigation
- React Hook Form for form handling
- Zod for form validation
- React Query for data fetching
- Axios for HTTP requests

-----

### Testing Libraries

Para garantir a qualidade do código, utilizamos as seguintes ferramentas:

[![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)](https://vitest.dev/) - Framework de testes unitários rápido e moderno, similar ao Jest

[![Testing Library](https://img.shields.io/badge/-TestingLibrary-%23E33332?style=for-the-badge&logo=testing-library&logoColor=white)](https://testing-library.com/) - Biblioteca para testar componentes React de forma mais próxima ao usuário real

[![jest-dom](https://img.shields.io/badge/jest--dom-c21325?style=for-the-badge&logo=jest&logoColor=white)](https://testing-library.com/docs/ecosystem-jest-dom/) - Extensão/plugin da `Testing Library` com matchers personalizados para testar elementos DOM

[![Playwright](https://img.shields.io/badge/Playwright-45ba4b?style=for-the-badge&logo=playwright&logoColor=white)](https://playwright.dev/) - Framework para testes end-to-end (E2E) automatizados

[![MSW](https://img.shields.io/badge/MSW-black?style=for-the-badge&logo=mock-service-worker&logoColor=white)](https://mswjs.io/) - Mock Service Worker para interceptar e simular chamadas de API em testes

Plugins adicionais:

[![jsdom](https://img.shields.io/badge/jsdom-yellow?style=for-the-badge&logo=javascript&logoColor=black)](https://github.com/jsdom/jsdom) - Implementação do DOM para ambiente Node.js, permitindo testar código browser-like

[![User Event](https://img.shields.io/badge/user--event-gray?style=for-the-badge&logo=testing-library&logoColor=white)](https://testing-library.com/docs/user-event/intro/) - Biblioteca para simular interações do usuário em testes

----

### API
- Bun.js with TypeScript
- Zod for validation
- JWT for authentication

----

### 📸 Screenshots

<div style="display: flex; gap: 10px;">
    <img src="./assets/signin.png" style="border-radius: 8px; width: 33%; transition: transform 0.3s; cursor: pointer;" onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'" alt="Login">
    <img src="./assets/dash.png" style="border-radius: 8px; width: 33%; transition: transform 0.3s; cursor: pointer;" onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'" alt="Dashboard">
    <img src="./assets/tab.png" style="border-radius: 8px; width: 33%; transition: transform 0.3s; cursor: pointer;" onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'" alt="Orders">
</div>