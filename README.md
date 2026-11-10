# FRAME — Portfolio 02 (Guará Agency)

Segundo modelo de portfólio da Guará Agency, reproduzindo a **composição visual do site [p.isera.dev](https://p.isera.dev/)**, conforme referência e captura fornecidas.

## Identidade visual mantida
- Desktop dividido em duas metades: carrossel fixo à esquerda e cartões roláveis à direita
- Header sobreposto à foto, cartões arredondados cinza-claro, perfil e links sociais
- Seção “Latest Travel” com tarjetas fotográficas e etiquetas no canto superior
- Galerias, páginas Travel, Discover, Blog e About; modo claro e escuro
- Responsividade em dispositivos móveis
- Conteúdo e identidade **demonstrativos e fictícios**

## Origem e licença
Referência open source: [ECarry/photography-website](https://github.com/ECarry/photography-website), autor Sera, licença MIT (Copyright 2024–present Sera). O projeto original tem Next.js, banco PostgreSQL, fotos em S3, autenticação e painel de administração.

Esta edição reimplementa a interface pública em HTML, CSS e JavaScript para GitHub Pages. O código Next.js original não foi incorporado, e esta versão não contém backend, painel, APIs ou recursos dinâmicos de banco. Há diferenças deliberadas em fotografias e conteúdo, por razões de direitos e dados pessoais; os elementos estruturais e a composição foram reproduzidos com base no código público e na referência visual.

## Customização
No final do `index.html`, editar os objetos `CONFIG`, `heroImages`, `cities`, `photos` e `stories`. Fotografias são ilustrativas e são carregadas de URLs públicas do Unsplash; substituir por imagens do cliente devidamente autorizadas. Links sociais ficam demonstrativos e não apontam para os perfis do autor original.

## Deploy
Workflow em `.github/workflows/pages.yml` publica automaticamente via GitHub Pages. URL esperada:

https://guaraagency-julio.github.io/modelo-portifolio-2/

## Modelo original
- [Demo](https://p.isera.dev/)
- [Código original](https://github.com/ECarry/photography-website/tree/main)
- [Apresentação 21st.dev](https://21st.dev/@ecarry/templates/photography-portfolio)

Os direitos relativos a fotografias e outras marcas pertencem a seus respectivos proprietários.
