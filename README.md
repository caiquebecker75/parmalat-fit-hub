# Parmalat Fit Hub · Ilha promocional 360°

Apresentação HTML da 75 LAB para a **Parmalat Fit (Lactalis)**: estratégia de shopper, arquitetura 360° da ilha, engenharia modular, rastreamento e cronograma até a instalação em 20 de outubro de 2026.

- **Versão de apresentação, 10 telas:** https://projetos.75lab.com.br/parmalat-fit-hub/
- **Versão completa, 26 telas:** https://projetos.75lab.com.br/parmalat-fit-hub/completo/

## Como apresentar

| Ação | Tecla |
| --- | --- |
| Avançar | seta direita, espaço, Page Down, clique nos botões, scroll, swipe |
| Voltar | seta esquerda, Page Up |
| Índice das telas | `M` |
| Tela cheia | `F` |
| Fechar índice ou lightbox | `Esc` |
| Ir direto a uma tela | `#<número>` na URL, ex.: `.../parmalat-fit-hub/#4` |

## As 10 telas

| # | Tela | Interação |
| --- | --- | --- |
| 01 | Abertura · os 12 segundos de decisão | Contador e trilha de capítulos clicável |
| 02 | O desafio · demanda alta, leitura fragmentada | Alterna a loja espalhada contra a ilha única, com as 8 famílias e os números de mercado |
| 03 | O shopper · necessidade e os quatro tempos | Linha do tempo com playhead sobre o render e frases de necessidade em rotação |
| 04 | O Parmalat Fit Hub · reveal e conceito | Verbos acendendo em sequência sobre o render |
| 05 | Arquitetura 360° | Planta clicável com quatro zonas, render e barra de participação por face |
| 06 | Leitura e acabamento | Simulador de distância de 5 m a 40 cm, halo animado, LED e materiais |
| 07 | Engenharia e capacidade | Vista explodida com slider, regra de blocagem e planograma |
| 08 | Plano de rastreamento 75 LAB | Fluxo animado com One Shot e On Timing |
| 09 | Mensuração e cronograma | Gantt animado até 20/10 e indicadores do piloto |
| 10 | Síntese e institucional | Volta aos 12 segundos e dados da 75 LAB |

A versão de 26 telas em `completo/` abre cada capítulo em profundidade: mercado, ecossistema, paradoxo, debrief, território competitivo, Face A, Face B, pontas A e B, halo, hierarquia, luz, engenharia, capacidade, galeria de 10 vistas com lightbox, rastreamento, mensuração e cronograma.

## Fontes do conteúdo

- `Briefing_Ilha_Parmalat_Fit_Agencia.pptx` (cliente)
- `Estrategia_Ilha_Parmalat_Fit_75LAB.docx` (75 LAB)
- `02_ESPECIFICACAO_TECNICA_3D.docx` e `03_DIMENSOES_E_PARAMETROS.csv`
- Renders conceituais do pacote Blender, em `assets/renders/`
- Packshots oficiais extraídos de parmalat.com.br, em `assets/packs/`
- Dados de mercado: Euromonitor, Nielsen Scantrack com dunnhumby, Worldpanel by Numerator

## Pendências de conteúdo

- Packshots de queijo fatiado proteico e creme de ricota proteico (tiles com moldura tracejada na tela 02)
- Razão social, CNPJ, cargo e telefone na tela institucional
- Modelo homologado das duas geladeiras, que congela as dimensões reais

## Técnico

Arquivo único `index.html`, palco fixo de 1600×900 escalado para a janela. Sem build e sem dependências externas além das fontes do Google. Imagens em WebP com fundo transparente.
