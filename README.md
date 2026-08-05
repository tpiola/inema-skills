# inema-skills — Manifesto de Skills INEMA para Hermes

Referencia remota (no GitHub) das skills de design/copy/monetizacao/SEO do
**inematds (INEMA.CLUB)**, consumidas sob demanda para **economizar espaço no
servidor e memória** (o Hermes NAO retem as skills locais; puxa do GitHub quando precisa).

## Como usar (Hermes)
1. Para usar uma skill sob demanda, clone o repo do inematds em /tmp:
   `git clone --depth 1 https://github.com/inematds/<repo> /tmp/inema`
2. Copie o SKILL.md + referencias para a pasta de skills, use, e DELETE depois
   (nunca retem no servidor — economia de espaço).

## Skills disponíveis
| Skill | Categoria | Subskills | Fonte |
|---|---|---|---|
| claude-seo | seo | seo, seo-schema, seo-hreflang, seo-competitor-pages, seo-programmatic | https://github.com/inematds/claude-seo |
| open-design | design | saas-landing, dashboard, docs-page, wireframe-sketch, finance-report, replit-deck | https://github.com/inematds/open-design |
| power-design | design | power-design | https://github.com/inematds/power-design |
| scroll-film-studio | design | scroll-film-studio | https://github.com/inematds/scroll-film-studio |
| skillmktv4 | marketing | criador-criativos, designer-senior, criador-reels, lancamento | https://github.com/inematds/skillmktv4 |
| timesmkt3 | marketing | copywriter-agent, video-engineering, marketing-research-agent | https://github.com/inematds/timesmkt3 |
| 33viralhooks | copy | hooks | https://github.com/inematds/33viralhooks |
| 8020 | vendas | vendas, estrategia | https://github.com/inematds/8020 |

## Regras
- Sempre `--depth 1` (clone raso, sem history pesado).
- Usar, limpar (`rm -rf /tmp/inema`) — não acumular skills no servidor.
- SEO local/Google: `claude-seo` cobre Search/Maps/schema. Combinar com skill
  `site-infraestrutura-venda` (padrão reidasvendas anti-AI-slop).
