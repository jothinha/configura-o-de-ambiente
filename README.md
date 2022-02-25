# Configurando o Ambiente para automatização com Cypress

### Dependências

#### Programas necessários para o funcionamento da automatização

Caso não tenha instalado em seu computador

Clique nos links para instalar o [hyper](https://hyper.is/), [VS Code](https://code.visualstudio.com/download) e o [gitHub](https://git-scm.com/downloads)

### Instalação do ambiente
Configurar o Hyper (terminal baseado em elétrons construído em HTML/CSS/JS 
- Acesse a página do [hyper](https://hyper.is/) e clique em Download.
![image](https://user-images.githubusercontent.com/81827985/151033470-43320c39-a359-41a1-b21e-bd91fee5a4a4.png)

- Baixar, instalar e configurar o Hyper.is
	- Colinha para integrar o Gitbash ao Hyper. Obs: alterar esses campos dentro do hyper
		- shell: 'C:\\Program Files\\Git\\git-cmd.exe',
		- shellArgs: ['--command=usr/bin/bash.exe', '-l', '-i'],
		- env: { 'TERM':'cygwin' },
- Themas importantes para instalar no VSCode
	- Hyper term Theme

### Criando um novo projeto (passo a passo)
- criar uma pasta com o nome desejado em C:
- Inicializar o projeto com estrutura do node:
    - npm init
- Responder as perguntas:
   - package name: get-started (nome do meu projeto)
   - description: Primeiro exemplo com Cypress
   - test command: npx cypress open
   - git repository:
   - keywords: palavras chaves para encontrar
   - author: Hulgo Rafael
   - license: MIT

- Após, executar esse comando: ele instala o cypress como sendo uma dependência dev
    - npm i cypress --save-dev

- Executar o script para abrir a interface do cypress
    - npm run test

