<p align="center">
  <img src="https://i.postimg.cc/NGWntpMc/Logo-Horizontal.png" alt="Logo do NotaGest" width="250"/>
</p>

<h1 align="center">Sistema de Gerenciamento de Notas Fiscais</h1>

<p align="center">
  Plataforma completa para o armazenamento, controle e exportação de notas fiscais de construção e reforma.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-15.2.4-4CAF50?style=flat&logo=next.js" alt="Next.js Badge"/>
  <img src="https://img.shields.io/badge/React-18.2.0-61DAFB?style=flat&logo=react&logoColor=white" alt="React Badge"/>
  <img src="https://img.shields.io/badge/Express-5.1.0-4CAF50?style=flat&logo=express" alt="Express Badge"/>
  <img src="https://img.shields.io/badge/MongoDB-8.18.1-4DB33D?style=flat&logo=mongodb" alt="MongoDB Badge"/>
  <img src="https://img.shields.io/badge/TypeScript-5.8.3-3178C6?style=flat&logo=typescript" alt="TypeScript Badge"/>
</p>

---
## 🏗️ Sobre

O **NotaGest** é um sistema inovador voltado ao **gerenciamento digital de notas fiscais relacionadas à construção e reforma de imóveis**, oferecendo uma plataforma completa que permite a **organização, controle e consulta rápida de documentos fiscais** de maneira prática.  

A plataforma possibilita aos usuários o **cadastro detalhado de imóveis**, o **envio e armazenamento de imagens das notas fiscais**, a **geração de relatórios em PDF** e a **exportação de dados em Excel**, garantindo que toda a documentação esteja sempre organizada e acessível. Com isso, o sistema **reduz significativamente o uso de papel**, promovendo uma gestão mais sustentável e eficiente.  

Além disso, o NotaGest foi desenvolvido pensando em diferentes perfis de usuários: desde **proprietários e administradores de imóveis**, até **empresas de construção e profissionais autônomos**, proporcionando uma **interface intuitiva**, **navegação simplificada** e funcionalidades voltadas à **facilidade de uso e agilidade na tomada de decisões**.  

O sistema também contribui para a **regularização de obras e reformas junto a órgãos públicos**, oferecendo suporte para **declarações fiscais**, **auditorias internas** e **consultas rápidas sobre despesas e investimentos em cada imóvel**.  

> 💡 O projeto foi desenvolvido no curso de **Desenvolvimento de Software Multiplataforma (DSM)** da **FATEC Votorantim**, integrando conceitos de front-end, back-end e banco de dados. A ideia é criar uma solução prática e moderna que atenda às necessidades reais do mercado de construção civil, trazendo **eficiência, organização e confiabilidade** para o gerenciamento de documentos fiscais.


## ⚙️ Arquitetura do Projeto

O sistema foi estruturado em duas principais camadas — **frontend** e **backend** — que se comunicam por meio de uma **API RESTful**.

| Módulo | Descrição | Principais Tecnologias |
|:--------|:-----------|:------------------------|
| **Frontend (NotaGest-TypeScript)** | Interface web onde o usuário interage, faz login, upload e gera relatórios. | Next.js, React, TypeScript, Tailwind CSS |
| **Backend (NotaGest-Express)** | API responsável pela autenticação, persistência de dados e upload de arquivos. | Node.js, Express, MongoDB, Multer, JWT |

## 📘 Documentação do Projeto

<p align="center">
  <img src="https://i.postimg.cc/R0hGcxDF/Diagrama-de-caso-de-uso.png" alt="Diagrama de Caso de Uso do NotaGest" width="600"/>
</p>
### 🗃️Swagger
- Backend: [Acesse aqui](https://backnotagest.onrender.com/api-docs/)
- Microsserviço: [Acesse aqui](https://micronotagest.onrender.com/api-docs/)
---

## 💡 Funcionalidades e Requisitos

O **NotaGest** foi desenvolvido com foco em **eficiência, organização e facilidade de uso**, atendendo tanto a usuários individuais quanto a empresas do setor de construção civil.  
A seguir estão as principais **funcionalidades** e **requisitos** do sistema:

---

### Requisitos Funcionais

#### Frontend (NotaGest-TypeScript)
- Permitir **autenticação de usuários** (login e cadastro).  
- Permitir o **cadastro de imóveis** com dados detalhados.  
- Realizar **upload de notas fiscais e recibos** em formato de imagem ou PDF.  
- Exibir **dashboard interativo** com gráficos gerados via **Recharts**.  
- Possibilitar a **geração de relatórios em PDF** utilizando **jsPDF**.  
- Permitir **exportação de dados em planilhas Excel**.  

#### Backend (NotaGest-Express)
- Disponibilizar uma **API RESTful** para comunicação entre o front-end e o banco de dados.  
- Implementar **middleware de autenticação via JWT** para garantir segurança nas rotas.  
- Integrar o sistema aos bancos de dados **MongoDB** e **MySQL**.  
- Realizar **criptografia de senhas** com **bcryptjs**.  
- Permitir o **upload de arquivos** com gerenciamento via **Multer**.  
- Gerar **documentação automatizada de rotas** utilizando **Swagger UI**.  

---

### Requisitos Não Funcionais

- **Usabilidade:** Interface intuitiva, desenvolvida com **Next.js** e **Tailwind CSS**.  
- **Desempenho:** Respostas rápidas das APIs e carregamento otimizado no front-end.  
- **Segurança:** Dados criptografados, tokens JWT e validações nas rotas de acesso.  
- **Disponibilidade:** Deploy contínuo nas plataformas **Vercel** (frontend) e **Render** (backend).  
- **Escalabilidade:** Estrutura modular que permite a expansão de novas funcionalidades.  
- **Compatibilidade:** Suporte aos principais navegadores modernos.  

---

## 📊 Entregas de Sprints  

### Sprint 1 — Redefinição de Senha (17–01 de outubro)
- Hospedagem em Nuvem (Frontend e Backend)
- Fazer página de redefinição de senha.
- Criar Readme (Documentação do Projeto)
- Criar Login do usuário.

![Sprint 1](https://github.com/user-attachments/assets/8a032a99-4f1a-4ffa-9873-8c8c97cd9d6b)


### Sprint 2 — Login / Cadastro (23–30 de outubro)
- Implementação das telas de **Login e Cadastro**
- Validação de credenciais (email/senha)
- Integração com backend (JWT e bcrypt)
- Middleware de autenticação  

![Sprint 2](https://i.postimg.cc/qBmkBsH9/sprint-2.png)

### Sprint 3 — Adicionar Arquivo (08-22 - novembro)
- Funcionalidades de upload, exclusão e gerenciamento de documentos
- Exportação de relatórios em PDF e Excel
- Implementação de filtros, paginação e validações
- Integração com armazenamento e APIs externas  

![Sprint 3](https://i.postimg.cc/FRr4NRWH/Sprint-3.png)  

---

### Resumo das Entregas

| Sprint | Período de Execução | Foco Principal | Principais Entregas |
|:--------|:---------------------|:---------------|:---------------------|
| **1** | 17–01 de outubro | Configuração e Base | Hospedagem em Nuvem, Página de Redefinição de Senha, Criação do README, Login Básico. |
| **2** | 23–30 de outubro | Autenticação Completa | Implementação de Login/Cadastro, Validação de Credenciais, Integração JWT/bcrypt, Middleware de Autenticação. |
| **3** | 08-22 - novembro | Gerenciamento de Notas | Upload/Exclusão/Gerenciamento de Documentos, Exportação para PDF e Excel, Filtros/Paginação. |

---

## 🧩 Tecnologias Utilizadas

| Categoria | Tecnologias |
|------------|--------------|
| **Frontend** | [Next.js](https://nextjs.org) • [React](https://react.dev) • [TypeScript](https://www.typescriptlang.org) • [Tailwind CSS](https://tailwindcss.com) • [AOS](https://michalsnik.github.io/aos/) • [Recharts](https://recharts.org) • [jsPDF](https://github.com/parallax/jsPDF) |
| **Backend** | [Express](https://expressjs.com) • [Node.js](https://nodejs.org) • [MongoDB](https://www.mongodb.com) • [MySQL2](https://www.npmjs.com/package/mysql2) • [JWT](https://jwt.io) • [bcryptjs](https://www.npmjs.com/package/bcryptjs) • [dotenv](https://www.npmjs.com/package/dotenv) • [Multer](https://www.npmjs.com/package/multer) |
| **Documentação** | [Swagger UI Express](https://www.npmjs.com/package/swagger-ui-express) • [Swagger JSDoc](https://www.npmjs.com/package/swagger-jsdoc) |


## 🌐 Acesso ao Projeto

O projeto está dividido em **Frontend** e **Backend**, que podem ser acessados pelos links abaixo:  

- Frontend: [Acesse aqui](https://nota-gest.vercel.app/)  
- Backend: [Acesse aqui](https://backnotagest.onrender.com/)
- Microsserviço: [Acesse aqui](https://micronotagest.onrender.com/)

## 🔹 Autores

- **Rodolfo Antunes de Almeida**  
- **Bianca Pichirilo Vergueiro Benatti**  
- **Jose Paulo de Oliveira**  
- **Ana Laura Martins Souto**
