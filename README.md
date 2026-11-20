# Kitanda Market — Protótipo

Protótipo navegável da loja online **Kitanda Market**, marca de camisolas inspiradas na Seleção de Angola, com envio para todo Portugal.

O protótipo serve para validar o design, a estrutura de páginas e os fluxos de compra antes da implementação na Shopify. Textos, preços e datas entre `[colchetes]` são marcadores, a preencher com o conteúdo real do cliente.

## Como ver

Não há dependências nem passo de build. Basta abrir o [index.html](index.html) num navegador:

```bash
# opcional: servir localmente
npx serve .
# ou
python -m http.server
```

## Estrutura

```
index.html   página única com HTML, CSS e JavaScript
img/         logótipo e fotografias dos produtos
```

O site é uma *single-page* com navegação por âncoras (`#loja`, `#produto`, `#carrinho`, …). Cada página é uma `<section class="view">` e o JavaScript mostra a vista correspondente ao hash do URL.

## Páginas incluídas

- **Início**: hero, coleções, mais vendidos, história do padrão, lista de espera e Instagram
- **Loja / Coleção**: grelha de produtos com filtros por coleção e ordenação
- **Novidades**
- **Produto**: galeria, versões, tamanhos, guia de tamanhos e barra fixa de compra no mobile
- **Carrinho**: página completa e gaveta lateral, com simulação do checkout da Shopify
- **Sobre**, **Contacto** e **FAQ** (com pesquisa)
- **Guia de tamanhos** e **Políticas** (envios, trocas, termos, privacidade)
- **Conta**: entrar e área de cliente
- **Pesquisa** e **404**

## Identidade visual

| Token | Cor | Uso |
|---|---|---|
| `--preto` | `#0A0A0A` | fundo |
| `--vermelho` | `#CC092F` | ações principais |
| `--amarelo` | `#FFCB00` | destaques e links |
| `--branco` | `#F5F5F0` | texto |

Tipografia: **Bebas Neue** para títulos e **Inter** para texto (Google Fonts).

## Créditos

O planeamento, o layout e a geração deste projeto foram co-criados com o [Claude](https://claude.ai), da Anthropic.
