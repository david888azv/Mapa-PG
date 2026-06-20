# Changelog — MAPA-PG (Física/Astronomia)

## v2.0 — Estratos CAPES 2025–2028 (2026-06-20)

**Novidade principal:** estratificação da produção de artigos em **A1–A8 + C** segundo a
**Ficha de Avaliação CAPES 2025–2028**, por **percentil do fator de impacto do periódico dentro da
área** (classes de 12,5%): A1 = 87,5–100% … A8 = 0–12,5%; **C = sem indicador de IF**.

### Adicionado
- **Filtro por estrato CAPES** (A1…A8, C) substituindo as 3 faixas de IF (Baixo/Médio/Alto).
  Cada estrato exibe o **percentil** e o **corte de fator de impacto da área**
  (ex.: `A1 · percentil 87,5–100% · IF ≥ 4,84`). Botões **Todos / Nenhum** e checkbox-mestre.
- Relatório detalhado de fator de impacto (HTML/TXT/CSV/gráficos) reescrito para os 9 estratos.
- Dados (`dados_fisica.json` e blob embutido): novos campos `estr_perm`, `estr_colab`,
  `estr_visit`, `estr_all` (A1..A8,C) + `metadata.estratos`. Gerados por
  `mapa-pg-multi/build/gerar_estratos_app.py` (paridade exata Σ A1–A8 == faixas de IF; C aditivo).

### Preservado
- A versão anterior (filtro por **faixas de fator de impacto**, v1.5) continua acessível em
  **`faixas-if.html`**, intacta. Snapshots de versão na raiz: `1.5-mapa-pg.html`, `2.0-mapa-pg.html`.

### Notas
- Apenas adições aos dados; nenhum valor pré-existente foi modificado.
- Service worker (`CACHE`) atualizado para `mapa-pg-v2.0.0` (necessário por ser cache-first).

## v1.5 e anteriores
Comparador da área de Astronomia/Física com 3 faixas de fator de impacto.
