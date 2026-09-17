# Parmalat Fit Hub · Ilha promocional 360°

Apresentação HTML da 75 LAB para a **Parmalat Fit (Lactalis)**: estratégia de shopper, arquitetura 360° da ilha, engenharia modular, rastreamento e cronograma até a instalação em 20 de outubro de 2026.

**No ar:** https://projetos.75lab.com.br/parmalat-fit-hub/

## Como apresentar

| Ação | Tecla |
| --- | --- |
| Avançar | seta direita, espaço, Page Down, clique nos botões, scroll, swipe |
| Voltar | seta esquerda, Page Up |
| Índice das 26 telas | `M` |
| Tela cheia | `F` |
| Fechar índice ou lightbox | `Esc` |
| Ir direto a uma tela | `#<número>` na URL, ex.: `.../parmalat-fit-hub/#10` |

## Estrutura

26 telas, cada uma com layout próprio e uma interação que explica algo do negócio:

1. Abertura · os 12 segundos de decisão
2. Agenda em trilha de 6 capítulos
3. Mercado · números com count-up
4. O ecossistema · 8 famílias clicáveis com packshots oficiais
5. O paradoxo · loja fragmentada contra ilha única
6. Leitura do desafio · funil de decupagem
7. O shopper · necessidades ligadas às zonas da ilha
8. A regra dos 12 segundos · linha do tempo com playhead sobre o render
9. Território competitivo · quadrante com o espaço vago
10. Reveal do Parmalat Fit Hub
11. Conceito "Sua fonte de proteína é aqui"
12. Arquitetura 360° · planta clicável com quatro zonas
13. Face A · Performance (40 e 60)
14. Face B · Lanche proteico (15g e 23g)
15. Pontas A e B · as duas geladeiras
16. O Halo Fit · com e sem halo
17. Hierarquia de comunicação · simulador de distância
18. Luz e materiais · luz ligada e desligada
19. Engenharia modular · vista explodida com slider
20. Capacidade, planograma e blocagem
21. A ilha por todos os ângulos · 10 vistas com lightbox
22. Plano de rastreamento 75 LAB · One Shot e On Timing
23. Mensuração do piloto
24. Cronograma até 20/10
25. Síntese
26. Institucional

## Fontes do conteúdo

- `Briefing_Ilha_Parmalat_Fit_Agencia.pptx` (cliente)
- `Estrategia_Ilha_Parmalat_Fit_75LAB.docx` (75 LAB)
- `02_ESPECIFICACAO_TECNICA_3D.docx` e `03_DIMENSOES_E_PARAMETROS.csv`
- Renders conceituais do pacote Blender, em `assets/renders/`
- Packshots oficiais extraídos de parmalat.com.br, em `assets/packs/`
- Dados de mercado: Euromonitor, Nielsen Scantrack com dunnhumby, Worldpanel by Numerator

## Pendências de conteúdo

- Packshots de queijo fatiado proteico e creme de ricota proteico (tiles com moldura tracejada na tela 04)
- Razão social, CNPJ, cargo e telefone na tela institucional
- Modelo homologado das duas geladeiras, que congela as dimensões reais

## Técnico

Arquivo único `index.html`, palco fixo de 1600×900 escalado para a janela. Sem build e sem dependências externas além das fontes do Google. Imagens em WebP com fundo transparente.
