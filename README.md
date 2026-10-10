# Lux Play — Site comercial

Landing page pública da Lux Play: https://luxplay.vercel.app/

## Estrutura
- `index.html`: HTML/CSS/JS sem frameworks ou build. Deploy automático via GitHub → Vercel.
- `lux.svg` e `lux.ico`: ícones da identidade visual.
- `robots.txt` e `sitemap.xml`: indexação.

## Alterar preços
No fim de `index.html`, encontre o array `prices`. Cada entrada contém:
`{months: N, label: "...", p: [semAdulto1Tela, comAdulto1Tela, semAdulto2Telas, comAdulto2Telas]}`.

Valores configurados em outubro/2026:

| Período | 1 tela sem adulto | 1 tela com adulto | 2 telas sem adulto | 2 telas com adulto |
| --- | ---: | ---: | ---: | ---: |
| 1 mês | R$ 20 | R$ 30 | R$ 25 | R$ 35 |
| 2 meses | R$ 40 | R$ 60 | R$ 50 | R$ 70 |
| 3 meses | R$ 55 | R$ 85 | R$ 70 | R$ 100 |
| 6 meses | R$ 100 | R$ 155 | R$ 130 | R$ 180 |
| 12 meses | R$ 190 | R$ 290 | R$ 240 | R$ 340 |

**Importante:** validar a disponibilidade de pacotes longos e 2 telas com o fornecedor antes de confirmar cada contratação.

## Atualizar comunicação
- Número do WhatsApp: buscar `5511980024737` no HTML.
- Totais do catálogo: buscar `+3.800`, `+38 mil` e `+13 mil`. São informações comerciais aproximadas, não uma medição em tempo real.
- Aplicativos apresentados: Smarters Player Lite, OneX, RX Purple, Lótus e Vuser; disponibilidade e eventuais cobranças variam.
- Instalador Windows: release verificado em `v1.5.0` no GitHub.
- A opção de catálogo adulto e o número de telas são definidos pelos seletores no navegador. O pagamento é tratado pelo atendimento, fora deste site.

## Verificações após publicar
1. Abrir a página no celular e no desktop.
2. Trocar 1/2 telas e com/sem adulto; conferir 5 valores.
3. Conferir botão de teste, CTA final e botões dos planos (WhatsApp).
4. Verificar a release para Windows e o FAQ.
5. Conferir a identidade visual, principalmente se o ícone for alterado.

Não adicione credenciais, URLs privadas de fornecedores ou dados de assinantes a este repositório público.
