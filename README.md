Formas do Goku (SSJ1 ao Instinto Superior)

Este é um site interativo que apresenta as principais transformações do Goku — desde o Super Saiyajin 1 até o Instinto Superior Completo.
O usuário pode clicar em qualquer forma e abrir um modal centralizado, contendo imagem e descrição da transformação.

📌 O mais legal: Todo o funcionamento dos modais e da navegação foi feito 100% em HTML + CSS, sem nenhuma linha de JavaScript.

🚀 Funcionalidades

Navegação totalmente feita com âncoras (#id)

Modais criados usando CSS puro com o seletor :target

Layout responsivo baseado em grid

Botões grandes, arredondados e organizados

Modal elegante com:

Botão “X” para fechar

Imagem da transformação

Texto explicativo

Visual limpo e estilizado para fãs de Dragon Ball

🧪 Tecnologias Utilizadas

HTML5

CSS3 (puro, sem frameworks)

Uso do :target para controlar exibição das seções

Grid Layout para organizar os botões

Estilização completa sem JavaScript

📁 Estrutura do Projeto
/
├── index.html
├── style.css
└── imagens/
    ├── ssj1.png
    ├── ssj2.png
    ├── ssj3.png
    ├── ssj4.png
    ├── ssj_blue.png
    ├── blue_kaioken.png
    ├── ui_incompleto.png
    ├── ui_completo.png
    └── suzano_instinto_superior.png


(os nomes podem variar conforme seu projeto)

🧩 Como o Site Funciona
🔘 Navegação

Cada botão é um link:

<a href="#ssj1">SSJ 1</a>

🪟 Exibição do modal (sem JS!)

As seções começam invisíveis:

section {
  display: none;
}


Quando o usuário clica em um botão, o CSS ativa:

section:target {
  display: block;
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}


✨ Isso cria um modal real apenas com CSS.

❌ Fechar o modal

O botão “X” simplesmente leva o usuário de volta ao topo:

<a href="#">X</a>

🎨 Design e Layout

Fundo em degradê suave

Cartões arredondados com leve transparência

Botões grandes e centralizados

Modal com sombra, bordas arredondadas e imagem centralizada

Tipografia simples e elegante

📸 Screenshots

(adicione aqui seus prints caso publique no GitHub)

🎯 Objetivo do Projeto

Este site foi criado para:

Praticar HTML e CSS

Dominar o uso do seletor :target para criar modais

Estudar grid layout e responsividade

Criar um projeto divertido sobre Dragon Ball

📄 Licença

Projeto livre para estudo e modificação.
