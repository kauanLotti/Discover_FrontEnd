# DevLinks

Agregador de links no estilo Linktree, feito como projeto final do curso **Discover** da [Rocketseat](https://www.rocketseat.com.br/), na disciplina da graduação em **Sistemas de Informação**.

A página reúne perfil, links úteis e redes sociais, com tema claro e escuro.

## Funcionalidades

- Perfil com foto e identificador
- Lista de links para conteúdos e projetos
- Ícones de GitHub, Instagram, YouTube e LinkedIn
- Alternância entre modo escuro e modo claro
- Layout responsivo (mobile e desktop)

## Tecnologias

- HTML5
- CSS3 (variáveis, Flexbox, media queries e animações)
- JavaScript
- [Ionicons](https://ionic.io/ionicons)
- Google Fonts (Inter)

## Como executar

Não há instalação de dependências. Basta abrir o projeto no navegador.

**Opção 1 — Live Server (VS Code)**

1. Clone o repositório:
   ```bash
   git clone https://github.com/kauanLotti/Discover_FrontEnd.git
   ```
2. Abra a pasta no VS Code.
3. Instale a extensão [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer).
4. Clique com o botão direito em `index.html` e escolha **Open with Live Server**.

**Opção 2 — arquivo local**

Abra `index.html` diretamente no navegador.

## Estrutura

```text
Discover_FrontEnd/
├── index.html      # marcação da página
├── style.css       # temas, layout e responsividade
├── script.js       # troca de tema e avatar
└── assets/         # imagens de fundo, avatares e ícones
```

O arquivo `script.js` aplica a classe `light` no documento e troca a foto de perfil conforme o tema.

## O que foi praticado

- Semântica HTML e organização da página
- CSS com variáveis para dois temas
- Interação simples com JavaScript (`classList.toggle`)
- Design responsivo com `media queries`
- Publicação do código no GitHub

## Créditos

Projeto baseado no **DevLinks** do curso Discover da Rocketseat.  
Conteúdo e layout de referência: [Rocketseat](https://rocketseat.com.br/).
