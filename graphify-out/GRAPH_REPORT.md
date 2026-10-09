# Graph Report - download-appatopy  (2026-10-09)

## Corpus Check
- 4 files · ~92,882 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 19 nodes · 12 edges · 9 communities (3 shown, 6 thin omitted)
- Extraction: 83% EXTRACTED · 17% INFERRED · 0% AMBIGUOUS · INFERRED: 2 edges (avg confidence: 0.9)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `c433c073`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- App Distribution & Installation
- Agent Rules & Workflows
- Brand Assets & Identity
- SAV Training Videos
- graphify.md
- graphify.md
- copilot-instructions.md
- Workflow de Operações Graphify
- Instruções do Copilot para Knowledge Graph

## God Nodes (most connected - your core abstractions)
1. `Página de Download do App ATOPY Fiomar` - 5 edges
2. `Vídeos de Treinamento SAV (Celular e Tablet)` - 3 edges
3. `Identidade Visual Logo ATOPY` - 3 edges
4. `graphify` - 1 edges
5. `Workflow: graphify` - 1 edges
6. `graphify` - 1 edges
7. `Distribuição APK Fiomar` - 1 edges
8. `Passo a Passo de Instalação do APK` - 1 edges
9. `Canal de Suporte WhatsApp ATOPY` - 1 edges
10. `Ativo de Logo Redimensionado` - 1 edges

## Surprising Connections (you probably didn't know these)
- `Página de Download do App ATOPY Fiomar` --references--> `Identidade Visual Logo ATOPY`  [EXTRACTED]
  index.html → assets/atopy-logo.png
- `Identidade Visual Logo ATOPY` --semantically_similar_to--> `Ativo de Logo Redimensionado`  [INFERRED] [semantically similar]
  assets/atopy-logo.png → logo/1.png
- `Vídeos de Treinamento SAV (Celular e Tablet)` --references--> `Thumbnail do Treinamento SAV Celular`  [EXTRACTED]
  index.html → videos-SAV/poster-celular.jpg
- `Vídeos de Treinamento SAV (Celular e Tablet)` --references--> `Thumbnail do Treinamento SAV Tablet`  [EXTRACTED]
  index.html → videos-SAV/poster-tablet.jpg
- `Identidade Visual Logo ATOPY` --conceptually_related_to--> `Ícone Web/Android Foguete ATOPY`  [INFERRED]
  assets/atopy-logo.png → logo/icon/android-chrome-192x192.png

## Hyperedges (group relationships)
- **Fluxo de Distribuição e Instalação do Aplicativo** — index_app_landing_page, index_download_fiomar_apk, index_installation_tutorial [EXTRACTED 0.95]
- **Treinamento Multimídia do SAV** — index_video_training_section, videos_sav_poster_celular_video_preview, videos_sav_poster_tablet_video_preview [EXTRACTED 0.85]

## Communities (9 total, 6 thin omitted)

### Community 0 - "App Distribution & Installation"
Cohesion: 0.50
Nodes (4): Página de Download do App ATOPY Fiomar, Distribuição APK Fiomar, Passo a Passo de Instalação do APK, Canal de Suporte WhatsApp ATOPY

### Community 2 - "Brand Assets & Identity"
Cohesion: 0.67
Nodes (3): Identidade Visual Logo ATOPY, Ativo de Logo Redimensionado, Ícone Web/Android Foguete ATOPY

### Community 3 - "SAV Training Videos"
Cohesion: 0.67
Nodes (3): Vídeos de Treinamento SAV (Celular e Tablet), Thumbnail do Treinamento SAV Celular, Thumbnail do Treinamento SAV Tablet

## Knowledge Gaps
- **13 isolated node(s):** `graphify`, `Workflow: graphify`, `graphify`, `Distribuição APK Fiomar`, `Passo a Passo de Instalação do APK` (+8 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **6 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Página de Download do App ATOPY Fiomar` connect `App Distribution & Installation` to `Brand Assets & Identity`, `SAV Training Videos`?**
  _High betweenness centrality (0.196) - this node is a cross-community bridge._
- **Why does `Vídeos de Treinamento SAV (Celular e Tablet)` connect `SAV Training Videos` to `App Distribution & Installation`?**
  _High betweenness centrality (0.098) - this node is a cross-community bridge._
- **Why does `Identidade Visual Logo ATOPY` connect `Brand Assets & Identity` to `App Distribution & Installation`?**
  _High betweenness centrality (0.098) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `Identidade Visual Logo ATOPY` (e.g. with `Ativo de Logo Redimensionado` and `Ícone Web/Android Foguete ATOPY`) actually correct?**
  _`Identidade Visual Logo ATOPY` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `graphify`, `Workflow: graphify`, `graphify` to the rest of the system?**
  _13 weakly-connected nodes found - possible documentation gaps or missing edges._