<!-- ===== HEADER ===== -->
<p align="right">
  <a href="./README.md" title="Read the README in english">
    <img
      src="https://img.shields.io/badge/lang-en-red?style=flat-square&labelColor=202024"
      alt="lang-en"
    />
  </a>
  <img
    src="https://img.shields.io/badge/lang-pt--br-gray?style=flat-square&labelColor=202024"
    alt="lang-pt-br"
  />
</p>

<h1 align="center">
  <a
    href="https://guipmdev-ignite-shop.vercel.app/"
    title="Acessar a aplicação web"
  >
    <img
      src="./src/assets/logo.svg"
      alt="Logo do Ignite Shop"
      height="60px"
    />
  </a>
</h1>

<p align="center">
  <img
    src="https://img.shields.io/github/languages/count/guipmdev/ignite-shop?color=%2304D361&labelColor=202024&label=linguagens"
    alt="Contagem de linguagens do repositório"
  />
  <img
    src="https://img.shields.io/github/repo-size/guipmdev/ignite-shop?labelColor=202024&label=tamanho do repo"
    alt="Tamanho do repositório"
  />
  <img
    src="https://img.shields.io/github/commit-activity/m/guipmdev/ignite-shop?color=black&labelColor=202024&label=atividade de commits"
    alt="Atividade de commits"
  />
  <a
    href="https://github.com/guipmdev/ignite-shop/commits/main"
    title="Visualizar commits do repositório"
  >
    <img
      src="https://img.shields.io/github/last-commit/guipmdev/ignite-shop?labelColor=202024&label=último commit"
      alt="Último commit"
    />
  </a>
  <a href="./LICENSE" title="Visualizar licença do projeto">
    <img
      src="https://img.shields.io/badge/license-MIT-brightgreen?labelColor=202024&label=licen%C3%A7a"
      alt="Licença do projeto"
    />
  </a>
  <a href="https://www.rocketseat.com.br/" title="Acessar o site da Rocketseat">
    <img
      src="https://img.shields.io/badge/Layout_por-Rocketseat-8257e5?labelColor=202024"
      alt="Designer do layout"
    />
  </a>
</p>

![Captura de tela da página inicial da aplicação](./src/assets/images/cover.webp)

<p align="center">
  <a href="https://guipmdev-ignite-shop.vercel.app/"
    >Acessar a aplicação web ↗</a
  >
</p>

<details>
  <summary>
    <h2>📒 Índice</h2>
  </summary>

- [📍 Visão geral](#-visão-geral)
- [✨ Funcionalidades](#-funcionalidades)
- [🤖 Demo](#-demo)
- [🎨 Layout](#-layout)
- [🛠 Tecnologias](#-tecnologias)
  - [Website](#website)
  - [Úteis](#úteis)
- [🚀 Primeiros passos](#-primeiros-passos)
  - [✔️ Pré-requisitos](#️-pré-requisitos)
  - [📦 Instalação](#-instalação)
  - [⚙️ Utilização](#️-utilização)
- [📄 Licença](#-licença)
- [👏 Reconhecimentos](#-reconhecimentos)
</details>

<!-- ===== PROJECT INFOS ===== -->

## 📍 Visão geral

Este projeto é uma aplicação web desenvolvida em _Next.js_ e _TypeScript_ de uma loja on-line fictícia que exibe os produtos na página inicial em um carrossel, possibilitando aos usuários visualizarem os detalhes clicando neles e fazer a compra por meio da plataforma de pagamento Stripe. Ela também tem uma página de sucesso que exibe os detalhes do que foi comprado.

O objetivo do Ignite Shop é proporcionar uma experiência de compra amigável e visualmente atraente, integrando-se a um processador de pagamento popular para simplificar o processo de compra para os clientes.

## ✨ Funcionalidades

👕 **Veja todas as peças de roupa** disponíveis de forma fácil

👀 **Veja mais detalhes** clicando no produto desejado

💳 **Escolha** o que desejar e **finalize o pagamento** pela Stripe (_apenas simbólico_)

🚚 Aguardar a compra chegar

## 🤖 Demo

https://github.com/guipmdev/ignite-shop/assets/136738335/137cef05-bfb4-460a-8c4e-ad68f410af36

## 🎨 Layout

O layout da aplicação foi projetado pela **Rocketseat** e está disponível no [Figma](https://www.figma.com/file/pipYkHza8fTHXsG1wjYsTZ/Ignite-Shop-%E2%80%A2-Projeto-React).

<p align="center">
  <img
    src="./src/assets/images/layout-cover.webp"
    alt="Imagem de capa do layout da aplicação web"
    width="50%"
  />
</p>

## 🛠 Tecnologias

As seguintes ferramentas foram usadas para desenvolver esse projeto:

### Website

<p>
  <a href="https://nextjs.org/">
    <img
      src="https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js"
      alt="Next.js"
    />
  </a>
  <a href="https://www.typescriptlang.org/">
    <img
      src="https://img.shields.io/badge/TypeScript-white?style=for-the-badge&logo=TypeScript"
      alt="TypeScript"
    />
  </a>
  <a href="https://eslint.org/">
    <img
      src="https://img.shields.io/badge/ESLint-101828?style=for-the-badge&logo=ESLint"
      alt="ESLint"
    />
  </a>
  <a href="https://github.com/rocketseat/eslint-config-rocketseat">
    <img
      src="https://img.shields.io/badge/Rocketseat_ESLint_config-gray?style=for-the-badge"
      alt="Rocketseat ESLint config"
    />
  </a>
</p>

<p>
  <a href="https://axios-http.com/">
    <img
      src="https://img.shields.io/badge/Axios-373747?style=for-the-badge&logo=Axios"
      alt="Axios"
    />
  </a>
  <a href="https://stripe.com/">
    <img
      src="https://img.shields.io/badge/Stripe-white?style=for-the-badge&logo=stripe"
      alt="Stripe"
    />
  </a>
</p>

<p>
  <a href="https://stitches.dev/">
    <img
      src="https://img.shields.io/badge/Stitches-151719?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIzNSIgaGVpZ2h0PSIzNSIgdmlldy1ib3g9IjAgMCAzNSAzNSIgZmlsbD0ibm9uZSI+CjxzdHlsZT4KICBwYXRoLCBjaXJjbGUgewogICAgc3Ryb2tlOiBoc2woMjAwIDclIDguNCUpOwogIH0KCiAgQG1lZGlhIChwcmVmZXJzLWNvbG9yLXNjaGVtZTogZGFyaykgewogICAgcGF0aCwgY2lyY2xlIHsKICAJICBzdHJva2U6IGhzbCgyNDAgMyUgOTMlKTsKICAgIH0KICB9Cjwvc3R5bGU+CjxjaXJjbGUgY3g9IjE3LjUiIGN5PSIxNy41IiByPSIxNC41IiBzdHJva2Utd2lkdGg9IjIiIC8+CjxwYXRoIGQ9Ik0xMi44MTg0IDMxLjMyMThMMzEuODcwOSAyMC4zMjE4IiAvPgo8cGF0aCBkPSJNMy4zMTgzNiAxNC44Njc0TDIyLjM3MDkgMy44Njc0MyIgLz4KPHBhdGggZD0iTTguNjUzMzIgMjkuMTA3N0wyNS45NzM4IDE5LjEwNzciIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgLz4KPHBhdGggZD0iTTkuMjE1ODIgMTYuMDgxNUwyNi41MzYzIDYuMDgxNTQiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgLz4KPHBhdGggZD0iTTEzLjIzMzQgMTQuMjI5N0wyMi41MDk5IDIxLjEwNzciIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgLz4KPHBhdGggZD0iTTE2LjY5NzMgMTIuMjMwMkwyNS45NzM2IDE5LjEwNzgiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgLz4KPHBhdGggZD0iTTkuMjE1ODIgMTYuMDgxNUwxOS4wNDU5IDIzLjEwNzgiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgLz4KPC9zdmc+"
      alt="Stitches"
    />
  </a>
  <a href="https://keen-slider.io/">
    <img
      src="https://img.shields.io/badge/Keen--Slider-gray?style=for-the-badge"
      alt="Keen-Slider"
    />
  </a>
</p>

_\* Confira o arquivo [<kbd>package.json</kbd>](./package.json)_

### Úteis

<p>
  <a href="https://git-scm.com/">
    <img
      src="https://img.shields.io/badge/Git-f1f1e9?style=for-the-badge&logo=git"
      alt="Git"
    />
  </a>
  <a href="https://nodejs.org/">
    <img
      src="https://img.shields.io/badge/Node.js-233056?style=for-the-badge&logo=node.js"
      alt="Node.js"
    />
  </a>
  <a href="https://figma.com/">
    <img
      src="https://img.shields.io/badge/Figma-white?style=for-the-badge&logo=figma"
      alt="Figma"
    />
  </a>
  <a href="https://fonts.google.com/">
    <img
      src="https://img.shields.io/badge/Google_Fonts-white?style=for-the-badge&logo=google-fonts"
      alt="Google Fonts"
    />
  </a>
  <a href="https://code.visualstudio.com/">
    <img
      src="https://img.shields.io/badge/VSCode-005293?style=for-the-badge&logo=visual-studio-code"
      alt="VSCode"
    />
  </a>
</p>

## 🚀 Primeiros passos

### ✔️ Pré-requisitos

Antes de você começar, certifique-se que você tem as seguintes ferramentas instaladas na sua máquina: [Git](https://git-scm.com/downloads), [Node.js](https://nodejs.org/en/download). Também é bom ter um editor para trabalhar com o código, como o [VSCode](https://code.visualstudio.com/Download).

### 📦 Instalação

1. Clone o repositório:

```sh
git clone https://github.com/guipmdev/ignite-shop/
```

2. Mude para o diretório do projeto:

```sh
cd ignite-shop
```

3. Instale as dependências:

```sh
npm install
```

### ⚙️ Utilização

1. Acesse/crie a sua conta na [Stripe](https://stripe.com/)

   - Crie uma loja, produtos e faça toda a configuração necessária

2. Obtenha as suas [_API keys_](https://dashboard.stripe.com/test/apikeys)

3. Renomeie o arquivo `.env.local.example` para `.env.local` e insira as informações necessárias:

```sh
mv .env.local.example .env.local
```

4. Inicie a aplicação web:

```sh
npm run dev
```

5. Acesse http://localhost:3000/ para visualizar a aplicação

## 📄 Licença

Este projeto está licenciado de acordo com os termos da licença `MIT`. Consulte o arquivo [LICENSE](./LICENSE) para mais informações.

## 👏 Reconhecimentos

> - Muito obrigado à [Rocketseat](https://www.rocketseat.com.br/) pelo layout e pelas dicas de como montar este projeto

<!-- ===== FOOTER ===== -->

---

<p align="center">
  Feito com 💙 por
  <a href="https://www.guipm.dev/"> @guipm.dev </a>
  - Fique à vontade para
  <a href="mailto:guipm.dev@gmail.com">entrar em contato comigo</a>!
</p>

<br />

<p align="center">
  <a href="#top">
    <b>↑&nbsp;&nbsp; Voltar ao topo &nbsp;&nbsp;↑</b>
  </a>
</p>
