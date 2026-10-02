# SyntaxWear

Landing page moderna de e-commerce especializada em tênis e sneakers, desenvolvida em HTML e CSS puro. O projeto simula um storefront de marca premium com visual elegante, responsivo e focado em conversão para venda online.

## Visão geral

A SyntaxWear é uma interface comercial para apresentação de produtos de moda urbana e esportiva. A página destaca:

- Hero banner com identidade visual forte e proposta de valor
- Navegação com categorias masculinas, femininas e outlet
- Seções de destaque para categorias de produtos
- Grade de produtos com foco em estética premium
- Footer com newsletter, redes sociais e navegação institucional
- Design responsivo para desktop e mobile

## Tecnologias utilizadas

- HTML5
- CSS3
- Arquivos SVG para logotipo e ícones
- Imagens JPG para banners e produtos
- Layout estático sem dependências de framework ou biblioteca

## Estrutura do projeto

```text
ecommerce-syntaxwear/
├── css/
│   ├── base.css
│   ├── layout.css
│   ├── reset.css
│   ├── variables.css
│   └── components/
│       ├── footer.css
│       ├── header.css
│       ├── hero.css
│       ├── product-category.css
│       └── product-grid.css
├── images/
│   ├── banners/
│   ├── icons/
│   ├── logo/
│   └── products/
├── index.html
├── README.md
└── .git/
```

### Descrição dos principais arquivos

- `index.html`: estrutura principal da landing page
- `css/base.css`: estilos globais e classes reutilizáveis
- `css/layout.css`: ajustes de layout e espaçamentos gerais
- `css/variables.css`: tokens de cor, fontes e valores padronizados
- `css/components/`: arquivos de estilo por seção do site
- `images/`: ativos visuais da marca, ícones, banners e produtos

## Funcionalidades implementadas

### Header e navegação
- Logo da marca
- Menu com categorias principais
- Acesso rápido para conta, ajuda e carrinho
- Versão mobile com menu responsivo

### Hero section
- Banner com imagem de destaque
- Texto promocional forte
- Botões de ação para ver modelos e comprar

### Categorias de produtos
- Cards para estilos como Casual, Esporte, Moderno e Futurista
- Efeito visual com overlay e botões sobre imagens

### Grid de destaque
- Organização em blocos com produtos e peças em destaque
- Estilo visual premium com contrastes e composição moderna

### Footer
- Newsletter para cadastro por e-mail
- Links de navegação por seção
- Ícones de redes sociais
- Rodapé com informações institucionais

## Como executar o projeto

### Opção 1: abrir diretamente no navegador

Basta abrir o arquivo `index.html` no navegador do seu computador.

### Opção 2: executar localmente com servidor

No terminal, na raiz do projeto, execute:

```bash
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000
```

## Personalização

Para ajustar a identidade visual do site, os pontos principais são:

- `css/variables.css`: alterar cores, fontes e espaçamentos base
- `css/components/*.css`: ajustes de cada seção
- `images/`: substituir imagens e banners da marca
- `index.html`: alterar textos, títulos, links e estrutura de conteúdo

## Observações

Este projeto é uma landing page estática e não possui:

- Backend
- Banco de dados
- Sistema de autenticação
- Carrinho funcional
- Checkout real

Ele serve como base visual e estrutural para uma loja de e-commerce, sendo ideal para apresentação de marca, protótipos e estudos de front-end.

## Próximos passos sugeridos

- Integrar catálogo dinâmico com JavaScript
- Adicionar filtro por categoria e preço
- Implementar carrinho de compras
- Criar páginas internas de produto e checkout
- Conectar com CMS ou API de e-commerce

## Autor

Projeto desenvolvido como estudo de desenvolvimento front-end e design de e-commerce em HTML/CSS.
