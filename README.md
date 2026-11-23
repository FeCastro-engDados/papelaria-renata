# Papelaria Renata – Pacote Festa Rápida

Landing page da Papelaria Renata (45 kits de lembrancinhas em 48h), feita em [Astro](https://astro.build). Projeto acadêmico do MBA Impacta – Digital Growth & AI-Driven Marketing.

## Onde editar

| O quê | Arquivo |
|---|---|
| Todos os textos, preços, FAQ e rodapé | `src/data/site.json` |
| Cores, fontes e espaçamentos | `src/styles/global.css` (variáveis no topo) |
| Estrutura das seções | `src/pages/index.astro` |
| Imagem do topo | `public/img/kit-lembrancinha.webp` |

Ainda faltam: WhatsApp real, endereço e CNPJ (em `rodape`, no `site.json`), além da foto real e do depoimento real (em `prova`).

## Rodar no computador

```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # gera o site final em dist/
```

## Publicar

Importe este repositório em https://vercel.com/new. A Vercel reconhece o Astro sozinha, e cada alteração enviada ao GitHub é publicada automaticamente.
