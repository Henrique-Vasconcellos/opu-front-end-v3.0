# Site Operação Urban [(Versão 3.0)](https://www.figma.com/file/n2yT16d3J0vCKdW5TogGb9/OPU?type=design&node-id=7%3A749&mode=design&t=w7z9y7gZMAcY5HZU-1)
 
 Projeto criado para _reformular_, _estruturar_ e _atualizar_ o site da **Operação Urban** com novas tecnologias (Versão 3.0).<br><br>
 Está sendo desenvolvido pelos amigos **Hugo Leonardo** (https://github.com/hugoleonardodev) e **Henrique Vasconcellos** (https://github.com/Henrique-Vasconcellos).

OBJETIVOS E FASES do Projeto:<br>
--------
* Criar a nova estrutura mais atrativa e funcional para os usuários.
* Criar o novo "Mapa da Patinação"
* Implementar um "Robo" para possibilitar a conexão dos patinadores ao mapa via WhatsApp.
  1. MSG de "Boas Vindas" quando um novo usuário entrar em uma sala
  2. MSG de boas vindas personalizadas para cada tipo de sala (se entrar na sala RJ, dados sobre a sala em específico)
  3. Possiblitar atalhos para mensagens como (links de salas, alerta de span, etc)
* Possibilitar visualizar duas páginas index diferentes;<br>
  1. Versão PC (Parecido com a versão 2 do site)<br>
  1. Versão Mobile (Mapa destacado e conectado com WhatsApp)
* Mesclar o projeto da campanha #FotoSozinha com o site.
  1. Projeto https://github.com/Henrique-Vasconcellos/campanha-fotosozinha
* Ranking da Patinação: agregador de dados de usuários, grupos e eventos. Rankear não só competições. Mas também a participação. Criação de eventos, etc.
 
-------
OUTRAS MELHORIAS (Objetivos Secundários):<br>

Em todo o site:
* Melhorar a barra de pesquisa
* Implemantar o preenchimento automático na pesquisa
  
Na página de FOTO<br>
* Rolagem infinita - Chegar no final da página, clicar para abrir mais fotos, chegando no final novamente e abrir mais fotos de novo.

Na página de AMIGOS<br>
* Ter a opção para o usuário criar seu "perfil" (cadastro) no site
* Criar uma área em que mostre os aniversáriantes

Na página específica do AMIGO (Usuário Cadastrado)<br>
* A página deverá informar o nível de conclusão do cadastro
* usuários que tiverem seu perfil mais completo terão algumas vantagens no site...

Na página de GRUPOS<br>
* Criar uma área para cadastro de grupos (perfil_2)
* um grupo estará vinculado a um usuário (perfil_1), este sendo o "responsável" e contato principal do grupo

Voltar com a LOJA<br>
* Oferecer serviço de compra de camisas (terceirizada) A loja pega o pedido, confecciona e envia
* Coninuarei estampando camisas apenas para o RJ
* Disponibilizar a logo para download para que todos possam estampar e confeccionar por conta própria
-------
-------
-------
VERSÕES ANTIGAS DO SITE
--------

(Versão 2.0)

O site atualmente está no ar com sua versão 2.0 (Não foi concluído a migração da versão 1.0)<br>
https://www.operacaourban.com.br

![image](https://github.com/Henrique-Vasconcellos/opu-front-end/assets/159064990/0fe7d898-9c78-4eaa-8563-dd6e17965c0e)

(Versão 1.0)

A primeira versão do site poderá ser verificada no link abaixo:
https://www.operacaourban.com.br/_antigo/index.php

![image](https://github.com/Henrique-Vasconcellos/opu-front-end/assets/159064990/8e1ce0d5-dec4-4657-b0b3-8385f408a2cf)

 -----
 
 This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
