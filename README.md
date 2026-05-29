# BESS — Seminário UTFPR

Apresentação dinâmica em **Slidev** para seminário técnico sobre integração de Battery Energy Storage Systems (BESS) ao sistema elétrico, com foco em curtailment, flexibilidade operacional, energy shifting, arbitragem e transição energética no Brasil.

## Objetivo

Substituir a apresentação PowerPoint tradicional por uma apresentação programável, versionável e visualmente mais adequada para seminário de pós-graduação, banca ou apresentação técnica.

## Estrutura

```txt
BESS/
├── slides.md
├── package.json
├── style.css
├── components/
│   ├── MetricCard.vue
│   └── ScenarioCard.vue
├── public/
│   └── figures/
│       ├── duck-curve.svg
│       ├── bess-market.svg
│       ├── curtailment.svg
│       ├── load-modulation.svg
│       ├── energy-shifting.svg
│       └── arbitrage.svg
└── .github/
    └── workflows/
        └── deploy.yml
```

## Como rodar localmente

Instale Node.js 18+ e execute:

```bash
npm install
npm run dev
```

A apresentação abrirá em:

```txt
http://localhost:3030
```

## Exportar para PDF

```bash
npm run export
```

## Publicar no GitHub Pages

O workflow em `.github/workflows/deploy.yml` faz build automático quando houver push na branch `main`.

Depois do primeiro build, ative em:

```txt
Repository Settings > Pages > Source > GitHub Actions
```

## Substituição pelas figuras originais do artigo

Coloque as figuras originais no caminho:

```txt
public/article/
```

com nomes, por exemplo:

```txt
gr2.jpg
gr3.jpg
gr4.jpg
...
gr15.jpg
```

Depois substitua nos slides os SVGs conceituais pelos arquivos do artigo, por exemplo:

```md
<img src="/article/gr4.jpg" class="figure-xl" />
```

## Comandos úteis

```bash
npm run dev       # apresentação em modo desenvolvimento
npm run build     # build estático
npm run export    # exportação em PDF
npm run format    # formatação opcional
```

## Observação

Esta versão foi estruturada para apresentação de 10–12 minutos, com narrativa técnica: problema → lacuna → objetivo → metodologia → resultados → limitações → perspectivas → conclusões.
