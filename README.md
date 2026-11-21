# Criando Agent Skills â€” Do CatÃ¡logo Ã  Sua Primeira Skill

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Curso **data-driven** sobre Agent Skills, no formato [INEMA.CLUB](https://inema.club).
Em vez de teoria solta, parte de uma **anÃ¡lise real de 39.366 skills** coletadas do [skills.sh](https://skills.sh).

ðŸ”— **Curso publicado:** https://inematds.github.io/skills-craft/

## O que tem aqui

| Caminho | O que Ã© |
|---|---|
| `index.html` | Landing do curso |
| `curso/trilha1..5/` | 5 trilhas Ã— (Ã­ndice + 5 mÃ³dulos) + mÃ³dulo 5.6 (Regras 2026) = 31 pÃ¡ginas. Cada trilha fecha com â­ As Melhores Â· ðŸ› ï¸ Como Criar Â· ðŸš€ Dicas AvanÃ§adas |
| `data/` | Dataset coletado do skills.sh (metadados das 39k skills, grupos, stats) |
| `corpus/examples/` | 25 arquivos `SKILL.md` reais das melhores skills (1 a 2 por grupo) |
| `BUILD-SPEC.md` | Spec de design usado para gerar as pÃ¡ginas no padrÃ£o INEMA |

## As 5 trilhas

1. ðŸŒ **Panorama do Ecossistema** â€” o que Ã© uma skill, por que o formato venceu, o mapa do skills.sh.
2. â­ **Qualidade & As Melhores** â€” como ler sinais de qualidade e vitrine das melhores por grupo.
3. ðŸ§¬ **Anatomia de uma Skill** â€” SKILL.md por dentro, progressive disclosure, a description que dispara.
4. ðŸ› ï¸ **Como Criar (o loop)** â€” do intent ao draft, e o loop testarâ†’avaliarâ†’iterar.
5. ðŸ§  **O Que Pensar** â€” quando vale uma skill, anti-padrÃµes, publicar/versionar/medir.

## Os dados (`data/`)

- `skills-index.json` â€” as 39.366 skills (id, name, installs, source, group).
- `sources.json` â€” 5.075 repositÃ³rios fonte com contagem.
- `by-group-top30.json` â€” top 30 por grupo.
- `selection-details.json` â€” 177 skills top com a `description` real.
- `stats.json` â€” estatÃ­sticas agregadas (lei de potÃªncia, distribuiÃ§Ã£o, volume por grupo).

### NÃºmeros-chave
- **39.366** skills Â· **5.075** repos Â· **53,9M** instalaÃ§Ãµes somadas Â· **16** grupos.
- Lei de potÃªncia: **60,2%** tÃªm <100 installs; sÃ³ **0,3% (131)** passam de 100k.
- As **100 mais instaladas** concentram **43,7%** de todos os installs.

> Coleta via API pÃºblica do skills.sh (`/api/search`) + `raw.githubusercontent` para os `SKILL.md`. Snapshot de 2026-06.

---

Feito para o portal [INEMA.CLUB](https://inema.club) Â· 2026

<!-- inema-backlink:v1 -->
## Mais no INEMA.CLUB

- [Ficha completa deste curso](https://www.inema.club/cursos/132-criando-agent-skills-do-catalogo-a-sua-primeira-skill/)
- [Guia: como aprender inteligÃªncia artificial](https://www.inema.club/aprender-inteligencia-artificial/)
- [Todos os cursos](https://www.inema.club/cursos/)
<!-- /inema-backlink:v1 -->

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>