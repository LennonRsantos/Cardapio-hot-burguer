<div align="center">
  <img src="./assets/logo%20burguer.png" alt="Hot Burguer Logo" width="120" style="border-radius: 50%;">
  <h1>🔥 Hot Burguer — Cardápio Digital & Delivery</h1>
  <p><b>O hambúrguer mais quente da cidade!</b></p>

  <p>
    <a href="#-sobre-o-projeto">Sobre</a> •
    <a href="#-funcionalidades">Funcionalidades</a> •
    <a href="#-tecnologias-utilizadas">Tecnologias</a> •
    <a href="#-como-executar-o-projeto">Como Executar</a> •
    <a href="#-autor">Autor</a>
  </p>
</div>

---

## 🧐 Sobre o Projeto

O **Hot Burguer** é um sistema de **cardápio digital interativo** desenvolvido para facilitar o autoatendimento e agilizar o processo de pedidos em hamburguerias e lanchonetes.

Através de uma interface moderna e intuitiva, os clientes podem navegar pelos produtos (hambúrgueres, combos e bebidas), adicionar itens ao carrinho, informar o endereço de entrega e **finalizar o pedido enviando a mensagem formatada diretamente para o WhatsApp do estabelecimento**.

---

## ✨ Funcionalidades

- [x] **Visualização do Menu:** Cardápio organizado por categorias (Hambúrgueres, Combos e Bebidas).
- [x] **Gerenciamento do Carrinho:**
  - Adição e remoção de itens dinamicamente.
  - Cálculo automático do valor total em Reais (R$).
  - Contador de itens em tempo real no rodapé.
- [x] **Validação de Horário de Funcionamento:**
  - Badge visual no cabeçalho indicando o horário (Seg à Dom - 18:00 às 23:00).
  - Bloqueio e notificação via Toast quando o estabelecimento estiver fechado.
- [x] **Integração com WhatsApp:**
  - Envio automático dos itens, quantidades, valores e endereço de entrega pré-formatados no WhatsApp do restaurante.
- [x] **Notificações em Tempo Real:** Feedback ao usuário utilizando a biblioteca Toastify.js.
- [x] **Design Responsivo:** Adaptado para dispositivos móveis, tablets e desktops com Tailwind CSS.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica da aplicação.
- **CSS3 / Tailwind CSS:** Estilização utilitária, responsiva e moderna.
- **JavaScript (ES6+):** Manipulação da DOM, regras de negócio do carrinho e integração do WhatsApp.
- **Toastify JS:** Exibição de alertas e notificações customizadas.
- **Font Awesome:** Ícones interativos.
- **Google Fonts (Roboto):** Tipografia oficial.

---

## 📁 Estrutura de Arquivos

```text
.
├── assets/             # Imagens dos produtos, logo e background
├── styles/
│   ├── style.css       # Configurações do Tailwind / Estilos customizados
│   └── output.css      # CSS compilado pelo Tailwind CLI
├── index.html          # Estrutura principal da página
├── script.js           # Lógica do carrinho, validações e integração WhatsApp
├── tailwind.config.js  # Configurações de tema do Tailwind CSS
└── package.json        # Dependências e scripts de desenvolvimento
