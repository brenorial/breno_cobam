# Projeto COBAM - Sistema de Reserva de Pré-Matrícula

Este projeto é uma interface web para gerenciar reservas de pré-matrícula de alunos, com um layout organizado em componentes reutilizáveis (navbar, sidebar e footer), estruturado com HTML, CSS e JavaScript puro.

## 📁 Estrutura de Pastas

```

project-root/
│
├── index.html # Página principal
├── styles/
│ └── style.css # Estilos globais do projeto
├── components/
│ ├── navbar.html # Menu superior (barra de navegação)
│ ├── sidebar.html # Menu lateral (ícones e links)
│ └── footer.html # Rodapé da aplicação
├── assets/
│ └── img/
│ └── cobam.png # Logo e outras imagens usadas no site
└── script.js # Script responsável por carregar os componentes

```

## ⚙️ Funcionamento

- O `index.html` é a página base da aplicação.
- O JavaScript (`script.js`) é executado ao carregar a página e injeta dinamicamente os componentes HTML no lugar dos elementos `#navbar`, `#sidebar` e `#footer`.
- Os ícones do menu lateral são carregados por meio de URLs externas (Flaticon).
- O layout é responsivo e usa **Flexbox** para organizar os elementos.

## 🧩 Componentização

Os arquivos HTML dentro de `components/` contêm blocos isolados de código:

- `navbar.html`: Título e informações do usuário.
- `sidebar.html`: Ícones de navegação lateral com labels.
- `footer.html`: Informações fixas no rodapé.

Essa estrutura facilita a manutenção e reaproveitamento dos elementos da interface.

## 🎨 Estilização

Todos os estilos estão centralizados em `styles/style.css`. Ele define:

- Layout da sidebar com efeito de expansão ao passar o mouse.
- Aparência dos botões, tabelas e título.
- Cores, fontes (Google Fonts - Montserrat) e responsividade.

## 📷 Imagens

As imagens como o logo (`cobam.png`) estão armazenadas dentro da pasta `assets/img/`. Os caminhos usados no HTML são relativos, como:

```html
<img src="assets/img/cobam.png" alt="Logo" />
```
