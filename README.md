# Atividade: Consulta de CEPs do Brasil - HTTP Request

Este projeto é uma aplicação web de página única (SPA) desenvolvida como atividade prática para o curso de **Desenvolvimento de Software Multiplataforma (DSM)**. A aplicação demonstra como realizar requisições HTTP externas para a API do ViaCEP utilizando JavaScript assíncrono (Fetch API), integrada a um servidor Node.js.

## 🚀 Tecnologias Utilizadas

* **Backend:** Node.js
* **Framework:** Express
* **Integração:** Fetch API (ViaCEP)
* **Variáveis de Ambiente:** Dotenv
* **Frontend:** HTML5, CSS3 e JavaScript (Vanilla)
* **Fontes:** Roboto (Google Fonts)

## 📋 Funcionalidades e Rotas

O servidor Express (`server.js`) está configurado para gerenciar a entrega dos recursos e a aplicação oferece as seguintes funcionalidades:

* **Página Principal (`/`):** Interface limpa e intuitiva para inserção de um CEP de 8 dígitos.
* **Consulta em Tempo Real:** Validação de campo e busca automática de dados (Logradouro, Bairro, Cidade e UF) diretamente da API ViaCEP.
* **Feedback ao Usuário:** Estados visuais para "Buscando...", mensagens de erro para CEPs inexistentes e exibição estilizada dos resultados de sucesso.
* **Efeitos Visuais:** Botão de busca com efeito magnético e animação de clique para uma melhor experiência de usuário.

## 📂 Estrutura de Arquivos

Conforme a implementação, o projeto organiza-se da seguinte forma:

* **`server.js`:** Configuração do servidor, carregamento de variáveis de ambiente (`.env`) e roteamento de arquivos estáticos.
* **`public/pages/index.html`:** Estrutura semântica da aplicação de consulta.
* **`public/assets/css/main.css`:** Estilização moderna utilizando Flexbox e design responsivo.
* **`public/assets/js/main.js`:** Lógica de manipulação do DOM e consumo da API externa.

## 🔗 Link de Acesso

O projeto está hospedado e pode ser acessado em:  
🚀 **[https://consulta-cep-dsm.vercel.app/](https://consulta-cep-dsm.vercel.app/)**

---
*Projeto desenvolvido para fins acadêmicos - Fatec / Centro Paula Souza.*
