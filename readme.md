# Sistema de Pedido Web

Projeto desenvolvido para a disciplina **Programação WebI**, turma ESN5, do curso de Engenharia de Software, sob orientação do professor Daniel Correia.  
Autor: Bruno Custódio de Castro Silva.

---

## 🔍 Visão Geral
Este sistema web tem como objetivo implementar um módulo de pedidos “1 × N” (um pedido com múltiplos itens) para auxiliar a gestão de vendas em um ambiente didático.  
Por meio dele, é possível:
- Cadastrar novos pedidos;
- Incluir múltiplos itens em cada pedido;
- Persistir dados;
- Apresentar interface simples de usuário para visualização dos pedidos.

---

## 🛠️ Funcionalidades principais
- Criação de um novo pedido com identificação única.
- Adição de diversos itens ao pedido (produto, quantidade, preço unitário).
- Visualização de todos os pedidos realizados, com detalhes de seus itens.
- Cálculo automático do valor total do pedido.
- Persistência de dados usando [ex: MySQL, PostgreSQL, ou arquivo local] *– ajustar conforme implementação*.
- Interface web responsiva leve (ex: usando [especificar framework front-end, se houver]).

---

## 📝 Tecnologias utilizadas
- Linguagem: **Java**
- Projeto Maven (arquivo `pom.xml` presente)
- Frameworks/back-end: [ex: Spring Boot, Jakarta EE] *– ajustar conforme implementação*
- Banco de dados: [ex: H2 / MySQL / PostgreSQL] *– ajustar conforme implementação*
- Front-end: [ex: HTML, CSS, JavaScript, Bootstrap] *– ajustar conforme implementação*

---

## 🚀 Como executar o projeto
1. Clone este repositório
   ```bash
   git clone https://github.com/browndark/sistemadepedidoaweb.git
