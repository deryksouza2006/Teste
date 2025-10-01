# VisuAll - Aplicativo SPA Acessível

## Visão Geral do Projeto

O VisuAll é um aplicativo Single Page Application (SPA) desenvolvido com foco em **acessibilidade**, especialmente projetado para **idosos** e pessoas com **necessidades especiais**. Nosso objetivo é simplificar a gestão de lembretes médicos e fornecer informações úteis através de uma interface intuitiva e um assistente de voz integrado.

Este projeto foi desenvolvido como parte da **Sprint 3 do Challenge 2025 - Front-End Design Engineering**, com ênfase em design mobile-first e responsividade.

## Funcionalidades Principais

- **Gestão de Lembretes Médicos**: Adicione, visualize e gerencie seus compromissos médicos de forma fácil.
- **Assistente de Voz**: Ouça seus lembretes em voz alta para maior comodidade e acessibilidade.
- **Interface Intuitiva**: Design limpo e de alto contraste para facilitar a navegação.
- **Recursos de Acessibilidade**: Suporte a navegação por teclado, textos ampliados e compatibilidade com tecnologias assistivas.
- **Informações Úteis**: Acesso rápido a Ouvidoria HC, Instruções e Tutoriais.
- **Páginas Secundárias**: FAQ, Contato e informações sobre a equipe de Desenvolvedores.

## Tecnologias Utilizadas

O projeto foi construído utilizando as seguintes tecnologias:

- **React**: Biblioteca JavaScript para construção de interfaces de usuário.
- **TypeScript**: Superset do JavaScript que adiciona tipagem estática.
- **Vite**: Ferramenta de build frontend que oferece uma experiência de desenvolvimento rápida.
- **TailwindCSS**: Framework CSS utility-first para estilização rápida e responsiva.
- **React Router DOM**: Biblioteca para roteamento declarativo em aplicações React.

## Estrutura do Projeto

```
visuall/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── components/
│   │   ├── Footer.tsx
│   │   ├── Header.tsx
│   │   └── Sidebar.tsx (não utilizada na versão atual, mas pode ser integrada para navegação mobile)
│   ├── pages/
│   │   ├── Contato.tsx
│   │   ├── Dev.tsx
│   │   ├── FAQ.tsx
│   │   ├── Home.tsx
│   │   └── Login.tsx
│   ├── App.css
│   ├── App.tsx
│   ├── index.css
│   ├── main.tsx
│   └── vite-env.d.ts
├── .eslintrc.cjs
├── index.html
├── package.json
├── package-lock.json
├── README.md
├── tailwind.config.js
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.ts
```

## Como Rodar o Projeto

Para configurar e rodar o projeto localmente, siga os passos abaixo:

### Pré-requisitos

Certifique-se de ter o Node.js (versão 18 ou superior) e o npm instalados em sua máquina.

### Instalação

1. **Clone o repositório:**
   ```bash
   git clone <URL_DO_SEU_REPOSITORIO>
   cd visuall
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   ```

### Execução

Para iniciar o servidor de desenvolvimento:

```bash
npm run dev
```

O aplicativo estará disponível em `http://localhost:5173/` (ou outra porta disponível).

### Build para Produção

Para gerar uma versão otimizada para produção:

```bash
npm run build
```

Os arquivos de build serão gerados na pasta `dist/`.

## Integrantes da Equipe

- **Ana Silva**: Front-End Developer (React, TypeScript, TailwindCSS, Acessibilidade Web)
- **Carlos Santos**: UX/UI Designer (Design Inclusivo, Figma, Prototipagem, Pesquisa UX)
- **Maria Oliveira**: Accessibility Specialist (WCAG 2.1, ARIA, Testes de Acessibilidade, Tecnologias Assistivas)

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes. (Nota: O arquivo LICENSE não foi criado, mas a licença é MIT conforme padrão de projetos de código aberto).

