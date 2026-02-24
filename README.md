# 🚗 FP Sellection

Landing page interativa para vitrine de carros esportivos e exclusivos.

Projeto desenvolvido com foco em animações modernas, transições suaves e experiência premium para o usuário.

---

## 📸 Demonstração

<img src="./img/1.png" alt="Preview do Projeto FP Sellection" />

---

## 🚀 Sobre o Projeto

A **FP Sellection** é uma landing page que apresenta um catálogo de carros esportivos de alto padrão com:

- Carrossel animado com transições suaves
- Navegação por setas (prev/next)
- Indicadores dinâmicos de posição
- Contador numérico do slide ativo
- Scroll suave entre seções
- Seção inicial (Hero)
- Formulário de contato estilizado

O projeto simula uma vitrine digital premium para concessionárias de carros esportivos.

---

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3 (Flexbox, Grid, Variáveis CSS, Animações)
- JavaScript Vanilla (DOM, Eventos, Manipulação de Classe)
- Google Fonts (Poppins, Inter, League Gothic)

---

## 🎯 Funcionalidades

### 🚘 Carrossel Dinâmico
- Alternância entre carros com animação horizontal
- Controle por botões
- Controle por indicadores
- Atualização automática do número do slide
- Uso de CSS Variables (`--calculation`) para controle de direção

### 🎨 Animações
- Transições suaves nos textos
- Rotação animada das imagens
- Efeito hover nos botões
- Mudança dinâmica de estado `.active`

### 📍 Navegação Suave
Scroll animado entre:
- Home
- Carros
- Contato

### 📩 Formulário
- Campos obrigatórios
- Layout moderno
- Estilização premium

---

## 📂 Estrutura do Projeto


fp-sellection/
│
├── index.html
├── style.css
├── script.js
└── img/
├── logo.png
├── 1.png
├── 2.png
├── 3.png
└── arrow.png


---

## 🧠 Lógica do Carrossel

O sistema funciona através de:

- Controle de índice `active`
- Alternância de classe `.active`
- Manipulação de variável CSS:
  
```js
list.style.setProperty('--calculation', 1)

Isso permite definir a direção da animação dinamicamente.

💻 Como Executar

Clone o repositório:

git clone https://github.com/seu-usuario/fp-sellection.git

Abra o arquivo:

index.html

Não é necessário backend ou dependências externas.

📱 Responsividade

O projeto possui media query para telas menores que 768px:

Ajuste do header

Redução do tamanho do título

Centralização do conteúdo

Ajuste de layout de navegação

📈 Possíveis Melhorias

Autoplay automático do carrossel

Integração real do formulário com backend

Adicionar loading animation

Implementar versão mobile-first

Deploy online (Vercel / Netlify)

👨‍💻 Autor

Desenvolvido por Cauã Santos
