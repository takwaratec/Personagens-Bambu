# AGENTS.md — Personagens Bambu

## Identidade
Repositório de construção dos 8 personagens do universo Bambu, com design system, 
biotipos, prompts de Stitch e roteiros para Google Flow.

## Estrutura
```
docs/                    ← Site MkDocs (GitHub Pages)
  assets/
    images/              ← Fotos otimizadas (JPEG 400px)
      transparent/       ← PNGs cortados sem borda
      variacoes/         ← Variações de cada personagem
    svg/                 ← Avatares SVG estilizados
  personagens/
    elenco.md            ← Fichas completas dos 8 personagens
    biotipos-e-roteiro.md ← Biotipos + galeria + Stitch prompts + roteiro Flow
    template.md          ← Template de ficha
  workflow/
    google-flow.md       ← Passo a passo do Google Flow
    referencia-rapida.md ← Compilado do workbook Marcos Lang
    cap-cut.md           ← Edição pós-produção
  design-system/         ← Paleta, biotipos, orientação Stitch
  prompts/               ← Biblioteca de prompts
  flow-projetos/         ← Links dos projetos Google Flow
assets/raw/              ← Referência local (não versionado)
```

## Personagens
1. **Bambusa** (F) — Âncora/mascote
2. **Vulgaris** (M) — Coadjuvante/entrevistador
3. **Sabia-mamona** (F) — Química, poliuretano vegetal
4. **Cacique-Asper** (M) — Saberes indígenas
5. **Taboca** (M) — Tabocauis do Acre, extrativismo
6. **Dr. Burocrata** (M) — Antagonista: monocultura/commoditie
7. **Tuldoides** (M) — Cooperativas/organização social
8. **Dr. Motosserra** (M) — Antagonista: negacionismo ético

## Convenções
- MkDocs com tema Material, PT-BR
- Imagens: JPEG 400px no site, PNG sem borda para edição
- SVGs em docs/assets/svg/ para avatares estilizados
- .gitignore exclui assets/raw/* (arquivos grandes locais)
- Git LFS não configurado (arquivos < 10MB)

## Deploy
- GitHub Actions em .github/workflows/gh-pages.yml
- Push para main → build automático → GitHub Pages
- URL: https://takwaratec.github.io/Personagens-Bambu/
