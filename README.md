# 📌 Vendas.Frontend — README

## 🛠️ Status:
🚧 Em andamento 🚧

## 🧩 Sobre o projeto

O Vendas.Frontend faz parte de uma prova de conceito (POC) construída para estudar micro‑frontends utilizando Module Federation.
Este projeto funciona como um dos módulos independentes que se integram dinamicamente à aplicação principal, expondo componentes e consumindo recursos compartilhados.

O cerne deste estudo reside na implementação de uma arquitetura de Microfrontends robusta e modular. O principal objetivo é estabelecer o Vendas.Frontend como a aplicação Host (contêiner), com a capacidade de integrar e consumir componentes de forma dinâmica e desacoplada a partir de dois outros projetos, que atuarão como Remotes.

Os projetos constituintes desta arquitetura são:

Vendas.Frontend: Atua como o Host principal, orquestrando a experiência do usuário e consumindo funcionalidades dos demais.

[Produtos.Frontend](https://github.com/Angelowh/Produto.Frontend): Um Remote que expõe componentes relacionados à gestão de produtos.

[Grafico.Frontend](https://github.com/Angelowh/Grafico.Frontend): Um Remote que disponibiliza componentes visuais (gráficos) para análise e exibição de dados.

## 🎯 Objetivo do estudo

- Demonstrar como micro‑frontends podem ser separados por domínio;

- Permitir deploy, versionamento e desenvolvimento independentes;

- Aprender Module Federation na prática usando projetos reais;

## 🏗️ Tecnologias usadas

- Angular

- Module Federation

- TypeScript

- CSS

## ▶️ Como executar

```bash
npm install
npm run start
```

## 🖼️ Prints da aplicação

