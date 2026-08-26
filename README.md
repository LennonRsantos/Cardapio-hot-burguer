# 🍔 Cardápio Digital & Sistema de Pedidos via WhatsApp

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=flat&logo=bootstrap&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat&logo=jquery&logoColor=white)

> Aplicação web interativa desenvolvida para otimizar o atendimento de estabelecimentos alimentícios (restaurantes, lanchonetes e hamburguerias), permitindo a navegação por produtos, gerenciamento de carrinho e checkout automatizado via WhatsApp.

---

## 🔗 Demonstração & Acesso

- **Repositório oficial**: [Cardapio_Digital no GitHub](https://github.com/LennonRsantos/Cardapio_Digital)
- **Deploy / Site Online**: [Acessar Cardápio Digital](https://lennonrsantos.github.io/Cardapio_Digital/) *(Ajuste o link se publicado no GitHub Pages)*

---

## 🚀 Funcionalidades Principais

- **📂 Cardápio Categorizado & Dinâmico**:
  - Filtros rápidos por categorias de produtos (Hambúrgueres, Pizzas, Bebidas, Sobremesas, etc.).
  - Renderização dinâmica com suporte a paginação ("Ver mais").
- **🛒 Carrinho de Compras Interativo**:
  - Adição, remoção e ajuste de quantidade de itens em tempo real.
  - Cálculo automático de subtotal, taxa de entrega e valor total do pedido.
  - Modal de checkout guiada em 3 etapas (Revisão de Itens ➔ Endereço ➔ Resumo).
- **📍 Busca Automática de Endereço (API ViaCEP)**:
  - Preenchimento automático de rua, bairro, cidade e estado ao digitar o CEP.
- **📲 Envio de Pedido via WhatsApp**:
  - Formatação e estruturação automática do pedido e dados de entrega em texto codificado para envio em um clique.
- **📱 Layout Responsivo & UX Aprimorada**:
  - Interface adaptada para smartphones, tablets e desktops.
  - Animações suaves de rolagem e feedback visual ao adicionar itens.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3**: Estruturação semântica da aplicação e estilização customizada.
- **JavaScript (ES6+) & jQuery**: Manipulação de estado do carrinho, controle de eventos do DOM e consumo de APIs.
- **Bootstrap**: Grid responsivo, componentes modais e estilização de formulários.
- **ViaCEP API**: Integração via requisição HTTP para busca de endereços por CEP.
- **WhatsApp Web API**: Comunicação direta para envio dos dados do pedido formatado.

---

## 📂 Estrutura de Arquivos

```text
Cardapio_Digital/
├── css/
│   ├── bootstrap.min.css
│   ├── fontawesome.css
│   ├── animate.css
│   └── main.css
├── js/
│   ├── jquery-1.12.4.min.js
│   ├── bootstrap.min.js
│   ├── dados.js       # Objeto de dados contendo os itens do cardápio
│   └── app.js         # Lógica da aplicação, carrinho e rotinas de checkout
├── img/               # Imagens dos produtos, ícones e assets visuais
└── index.html         # Página principal da aplicação
