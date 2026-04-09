# LLM Wiki Schema

Use this schema for all generated wiki content.

## Directory layout
- `content/{topic}/overview.md`
- `content/{topic}/sources/*.md`
- `content/{topic}/concepts/*.md`
- `content/{topic}/entities/*.md`
- `content/{topic}/synthesis/*.md`

## Page rules
- All pages should use clear titles.
- Use full-path wikilinks from content root.
- Keep source summaries separate from concepts and synthesis.
- Add citations when facts come from external sources.
- All prose content should be bilingual by default:
  - English paragraph
  - `<div class="zh-trans">中文翻译</div>` immediately after

## Suggested sections
### overview.md
- Topic summary
- Key concepts
- Key entities
- Source map
- Open questions

### source page
- Source metadata
- Summary
- Key claims
- Notable details
- Related pages

### concept page
- Definition
- Why it matters
- Related concepts
- Related entities
- Sources

### entity page
- What it is
- Role in topic
- Related concepts
- Sources

### synthesis page
- Question or theme
- Cross-source comparison
- Main conclusions
- Uncertainties
- Sources
