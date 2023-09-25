<h1 align="center">RocketPlayer - Zustand</h1>

<p align="center">
  <img 
    src="https://img.shields.io/badge/React-18.2.15-blue" 
    alt="React Ver. 18.2.15"
  />
  <img 
    src="https://img.shields.io/badge/Typescript-5.0.2-blue"
    alt="Typescript Ver. 5.0.2" 
  />
  <img
    src="https://img.shields.io/badge/NLWIA-2023-green" 
    alt="Ignite-2023"
  />
  <img 
    alt="License"
    src="https://img.shields.io/static/v1?label=license&message=MIT&color=E51C44&labelColor=0A1033"
  />
</p>

<div align="center">

  ![Last commit](https://img.shields.io/github/last-commit/Jonathan-Rios/ignite-rocketplayer-zustand?color=4DA1CD 'Last commit') &nbsp;
  ![Repo size](https://img.shields.io/github/repo-size/Jonathan-Rios/ignite-rocketplayer-zustand?color=4DA1CD 'Repo size') &nbsp;
  ![Languages](https://img.shields.io/github/languages/count/Jonathan-Rios/ignite-rocketplayer-zustand?color=4DA1CD 'Languages') &nbsp;
  
</div>

<br>

<h3 align="center">Imagem prévia da aplicação</h3>
 
<div align="center">
  <img src=".github/project-preview.png?style=flat" alt="Cover" />
</div>

<br>

## 💻 Projeto
Essa aplicação foi desenvolvida para estudos seguindo os ensinamentos da **[Rocketseat](https://www.rocketseat.com.br/)** na semana NLWIA.

Aplicação para auxiliar na criação de títulos, descrições de vídeos (ou o que quiser configurar) usando IA do ChatGPT, basta fazer o upload que ela obtém o audio e te retorna opções para você escolher.

## 🧪 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [ViteJs](https://vitejs.dev/)
- [React](https://reactjs.org)
- [TypeScript](https://www.typescriptlang.org/)
- [Zustand](https://zustand-demo.pmnd.rs/)
- [Tailwind](https://tailwindcss.com/)


## 🚀 Como executar
Esse projeto precisa da api para funcionar, que é encontrada nesse [repositório](https://github.com/Jonathan-Rios/nlwia-upload-ia-api.git).

Clone o projeto e acesse a pasta do mesmo.

```bash
$ git clone https://github.com/Jonathan-Rios/ignite-rocketplayer-zustand.git

$ cd ignite-rocketplayer-zustand
```

Para iniciá-lo, siga os passos abaixo:
```bash
# Instalar as dependências
$ npm install

# Iniciar a API de exemplo
$ npm run server

# Iniciar o projeto
$ npm run dev
```
- Aparecerá no terminal o link de acesso da aplicação, geralmente na porta http://localhost:5173/.

## 📝 License

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](./LICENSE.md) para mais detalhes.

<br />


## 📓 Anotações pessoais

<h3>Criando o projeto e suas dependências </h3>

```bash
  ➜ npm create vite@latest ignite-rocketplayer-zustand --use-npm 
      Need to install the following packages:
        create-vite@4.4.1
      Ok to proceed? (y) y
      ✔ Select a framework: › React
      ✔ Select a variant: › TypeScript
  
  ➜ npm i -D eslint @rocketseat/eslint-config
  # Adicione "@rocketseat/eslint-config/next" no .eslintrc.cjs dentro de extends.
  # Mais detalhes de como configurar: https://github.com/Rocketseat/eslint-config-rocketseat
  
  ➜ npm install -D tailwindcss postcss autoprefixer
  ➜ npx tailwindcss init -p # Para rodar no Vite precisa ter esse -p

  ➜ npm i react-player

  ➜ npm i -D tailwind-scrollbar #Tem que adicionar o plugin em tailwind.config.js

  ➜ npm install @radix-ui/react-collapsible

  ➜ npm i axios 
  ➜ npm i lucide-react 
  
  ➜ npm i zustand

  ➜ npm i -D json-server
  ➜ npm i -D vitest
```   
<br />


---
<br />

<a href="https://github.com/Jonathan-Rios">
 <img src="https://github.com/Jonathan-Rios.png" width="100px;" alt="" />
 <br />
 <sub><b>Jonathan Rios Sousa</b></sub></a>

💠 NeverStopLearning 💠

[![Linkedin Badge](https://img.shields.io/badge/-Jonathan-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/jonathan-rios-sousa-19b3431b6/)](https://www.linkedin.com/in/jonathan-rios-sousa-19b3431b6/) 
[![Gmail Badge](https://img.shields.io/badge/-jonathan.riosousa@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:jonathan.riosousa@gmail.com)](mailto:jonathan.riosousa@gmail.com)