# MAPA-PG — Monitoramento e Analise de Producao Academica da Pos-Graduacao

Sistema interativo em HTML5 para acompanhamento, gestao e analise comparativa de programas de pos-graduacao brasileiros na area de Astronomia / Fisica, com dados do Portal de Dados Abertos da CAPES.

<p align="center">
  <img src="logos/unb_marca.jpg" alt="Universidade de Brasilia" height="100"/>
</p>

---

## Autor

**Prof. David L. Azevedo**
Instituto de Fisica, Universidade de Brasilia (UnB)
E-mail: david888azv@unb.br

---

## Funcionalidades

- Comparativo de produtividade entre programas com notas CAPES 5, 6 e 7
- Analise ao longo de tres quadrienios (2013-2016, 2017-2020, 2021-2024)
- Filtros por nota, quadrienio, regiao, IES, categoria docente, tipo de producao e estrato de fator de impacto
- Media nacional de todas as areas (opcional) para comparacao nos graficos e tabelas
- Graficos interativos (barras, linhas, evolucao temporal)
- Tabelas detalhadas com ranking de programas
- Relatorio de fator de impacto (OpenAlex)
- Exportacao de dados (CSV), graficos (PNG) e relatorios (TXT)
- Glossario completo de 66 programas de Fisica/Astronomia com datas de fundacao

## Como Executar

1. Abra o arquivo `1.4-mapa-pg.html` em qualquer navegador moderno (Chrome, Firefox, Edge, Safari)
2. Na primeira abertura e necessaria conexao com internet para carregar Chart.js via CDN
3. Pronto! O sistema carrega automaticamente o `dados_fisica.json`

**Compativel com Windows, Linux e macOS. Nenhuma instalacao necessaria.**

## Estrutura

```
mapa-pg/
  1.4-mapa-pg.html   - Aplicacao principal (HTML5, autocontida)
  help-doc.html      - Documentacao, fontes de dados e glossario de siglas
  dados_fisica.json  - Dados pre-processados de 67 programas
  LEIA-ME.txt        - Instrucoes em portugues
  logos/             - Logos das agencias de fomento
```

## Fonte dos Dados

Todos os dados utilizados foram obtidos do [Portal de Dados Abertos da CAPES](https://dadosabertos.capes.gov.br/), como parte da iniciativa do Governo Federal de transparencia e acesso a informacao publica (Lei de Acesso a Informacao — Lei n. 12.527/2011). Os dados sao publicos e de livre acesso.

As URLs para download de todos os dados brutos estao documentadas no arquivo `help-doc.html`.

## Acknowledgments

This work was supported by the Brazilian research agencies CAPES and CNPq. The authors acknowledge the Distrito Federal Research Foundation (FAPDF) for financial and equipment support (Grants 04/2017 and 09/2022). D.L.A. acknowledges additional support from CNPq research productivity fellowship (Proc. 306456/2025-7).

<p align="center">
  <img src="logos/capes.jpg" alt="CAPES" height="60"/>&nbsp;&nbsp;&nbsp;
  <img src="logos/cnpq.png" alt="CNPq" height="60"/>&nbsp;&nbsp;&nbsp;
  <img src="logos/fapdf.png" alt="FAPDF" height="60"/>
</p>

---

**MAPA-PG** v1.4 | Abril 2026 | Prof. David L. Azevedo | Universidade de Brasilia (UnB)
