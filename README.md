# SyntaxWear E-commerce

Um projeto de página de destino de comércio eletrônico simples e responsivo para uma loja de calçados fictícia chamada SyntaxWear.

## Visão Geral

Este projeto é uma implementação de front-end para uma página de destino de uma loja de calçados online. Ele apresenta um design moderno e limpo, com seções para produtos em destaque, categorias e uma newsletter. A página é totalmente responsiva e se adapta a diferentes tamanhos de tela, de dispositivos móveis a desktops.

## Funcionalidades

- **Design Responsivo:** Layout que se adapta a dispositivos móveis, tablets e desktops.
- **Cabeçalho e Navegação:** Navegação principal com links para categorias e informações da loja.
- **Seção Hero:** Seção de destaque com um call-to-action.
- **Categorias de Produtos:** Seção para exibir diferentes categorias de produtos.
- **Grid de Produtos:** Uma grade para exibir produtos em destaque.
- **Newsletter:** Formulário de inscrição para a newsletter.
- **Rodapé:** Links para redes sociais, informações da empresa e outras páginas.

## Tecnologias Utilizadas

- **HTML5:** Para a estrutura da página.
- **CSS3:** Para estilização e layout, utilizando o modelo BEM (Block, Element, Modifier) para uma estrutura de CSS organizada e modular.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

```
ecommerce-syntaxwear/
├── components/
│   ├── collection-highlight.html
│   ├── footer.html
│   ├── header.html
│   ├── hero.html
│   ├── newsletter.html
│   ├── product-categories.html
│   └── product-grid.html
├── css/
│   ├── base/
│   │   ├── _reset.css
│   │   ├── _typography.css
│   │   └── _variables.css
│   ├── layout/
│   │   ├── _footer.css
│   │   ├── _header.css
│   │   ├── _hero.css
│   │   ├── _product-categories.css
│   │   └── _product-grid.css
│   ├── utils/
│   │   ├── _accessibility.css
│   │   └── _helpers.css
│   └── main.css
├── images/
│   ├── assets/
│   │   ├── banners/
│   │   ├── logo/
│   │   ├── misc/
│   │   └── products/
│   ├── favicons/
│   └── icons/
├── index.html
└── README.md
```

- **`index.html`**: O arquivo principal da página.
- **`components/`**: Contém os componentes HTML reutilizáveis.
- **`css/`**: Contém todos os arquivos de estilo.
  - **`base/`**: Estilos base como reset, tipografia e variáveis.
  - **`layout/`**: Estilos para as principais seções da página.
  - **`utils/`**: Utilitários de CSS.
  - **`main.css`**: O arquivo principal que importa todos os outros arquivos CSS.
- **`images/`**: Contém todas as imagens, ícones e outros ativos visuais.

## Como Usar

Para visualizar o projeto, basta abrir o arquivo `index.html` em seu navegador de preferência.

```bash


# Navegue até o diretório do projeto
cd ecommerce-syntaxwear

# Abra o index.html no seu navegador
```

