## Setup TypeScript Project

Projeto com intuito de servir de setup inicial para projetos utilizando **Typescript** com boas práticas.

### ⚙️ Tools

- **[Eslint](https://eslint.org/ 'Eslint')**
- **[Pretier](https://prettier.io/ 'Pretier')**
- **[EditorConfig](https://editorconfig.org/ 'EditorConfig')**
- **[Husky](https://www.npmjs.com/package/husky 'Husky')** - Só consegui fazer funcionar na versão **4.2.3**
- **[Lint Staged](https://www.npmjs.com/package/lint-staged 'Lint Staged')**
- **[Pretty Quick](https://www.npmjs.com/package/pretty-quick 'Pretty Quick')**
- **[Git commit msg linter](https://www.npmjs.com/package/git-commit-msg-linter 'Git commit msg linter')**

### 🗒 Features

- Utilizando o comando abaixo: **yarn lint**, é possível verificar se todos os arquivos estão de acordo com as regras estabelecidas e preparados para o commit.

```
$ yarn lint
```

- Boas práticas para mensagens de commits também é importante, sendo assim segue tipos permitidos by **[Git commit msg linter](https://www.npmjs.com/package/git-commit-msg-linter 'Git commit msg linter')**: 

	**Tipos:**
  	- **feat:**     A new feature.
    - **fix:**      A bug fix.
    - **docs:**     Documentation only changes.
    - **style:**    Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc).
    - **refactor:** A code change that neither fixes a bug nor adds a feature.
    - **test:**     Adding missing tests or correcting existing ones.
    - **chore:**    Changes to the build process or auxiliary tools and libraries such as documentation generation.
    - **perf:**     A code change that improves performance.
    - **ci:**       Changes to your CI configuration files and scripts.
    - **build:**    Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm).
    - **temp:**     Temporary commit that won't be included in your CHANGELOG.

	**Exemplos:**
	
		$ git commit -m "feat: creating a new UserController"
		$ git commit -m "refactor: remove code duplicate on UserController"
		$ git commit -m "docs: adding doc of new route of creating a new user" 
	

## ㊗️ Considerações

- Caso queiram dar palpites e implementações a serem feitas, basta entrar em contato, não perde tempo.

- Projeto desenvolvido por:

  - <a href="https://github.com/rafaelsanzio">
      <img src="https://img.shields.io/badge/-Rafael%20Sanzio-000000?style=flat&logo=GitHub&logoColor=#000000" />
    </a>

  - <a href="https://www.linkedin.com/in/rafael-sanzio-012778143/">
      <img src="https://img.shields.io/badge/-Rafael%20Sanzio-0077B5?style=flat&logo=LinkedIN&logoColor=#000000" />
    </a>

- **Já que chegou até aqui, aproveitar e deixar uma 🌟 para o repositório**
