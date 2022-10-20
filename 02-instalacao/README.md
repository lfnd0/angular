<p align="center">
    <img src="../.github/angular-logo.png" alt="Angular" width=240>
</p>

<h1 align="center">
  Instalação do Angular
</h1>


### Instalando os recursos e links de instalação do Angular CLI

#### Dependências necessárias:
- [Node Version Manager (NVM)](https://github.com/nvm-sh/nvm#installing-and-updating)
- [Node.js](https://github.com/nvm-sh/nvm#long-term-support)
- [Angular CLI (localmente)](https://medium.com/@starikovs/how-to-use-angular-cli-locally-729dbb6707dd)
- [Angular CLI](https://angular.io/cli)


### Angular CLI

#### Comandos iniciais do Angular CLI:
- Criar um novo projeto:
  ```shell
  npx -p @angular/cli ng new nome-do-projeto
  ```
- Helper:
  ```shell
  npx ng --help
  ```
- Executar o projeto:
  ```
  npx ng serve
  ```

### Arquitetura/estrutura
```
.
├── angular.json (Definições/configurações do projeto Angular)
├── .browserslistrc (Configuração/suporte para os navegadores)
├── .editorconfig
├── .gitignore
├── karma.conf.js (Responsável pelos testes)
├── package.json (Armazena as dependências e os scripts para executar a aplicação)
├── package-lock.json
├── README.md
├── src (Diretório para o armazenamento do código do projeto)
│   ├── app (Armazena os componentes da aplicação)
│   │   ├── app.component.html (HTML)
│   │   ├── app.component.scss (SCSS)
│   │   ├── app.component.spec.ts (Teste)
│   │   ├── app.component.ts (Componente)
│   │   ├── app.module.ts (Módulo)
│   │   └── app-routing.module.ts (Rota)
│   ├── assets (Destinado aos arquivos estáticos)
│   │   └── .gitkeep
│   ├── environments (Armazena os arquivos responsáveis pelas variáveis de ambiente)
│   │   ├── environment.prod.ts
│   │   └── environment.ts
│   ├── favicon.ico
│   ├── index.html (Template HTML principal)
│   ├── main.ts
│   ├── polyfills.ts
│   ├── styles.scss (Modelo para as folhas de estilo SCSS)
│   └── test.ts (Modelo para a criação de testes)
├── tsconfig.app.json (Definições do TypeScript)
├── tsconfig.json (Configurações do TypeScript)
└── tsconfig.spec.json (Responsável pela configuração dos testes)
```
