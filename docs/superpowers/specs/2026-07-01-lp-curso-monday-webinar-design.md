# Design Spec — LP Curso Monday (público do webinar Cemitério de Softwares)

**Data:** 2026-07-01  
**Arquivo de saída:** `C:\Users\joaoh\Documents\VS Studio\LP_CursoMonday_CS\lp-monday-webinar.html`

---

## Objetivo

Página de vendas do curso de Monday.com da SquadHub, direcionada ao público que se inscreveu no webinar "Cemitério de Softwares" (02/07/2026) — tanto quem assistiu ao vivo quanto quem recebeu os e-mails mas não compareceu. A LP vende direto ao checkout, sem formulário de captura.

---

## Audiência

- Donos/gestores de PMEs com 2-50 funcionários
- Já expostos à dor de "acúmulo de softwares" (webinar ou e-mails do funil)
- **Não** exige reapresentação do problema do zero (público quente/morno)
- **Não** exige apresentação do Eduardo Leal (já o conhecem do evento)

---

## Identidade visual

Reaproveita 100% os tokens do `cemiterio.html`:

| Token | Valor |
|---|---|
| Background principal | `#050505` |
| Surface | `#080F1A` |
| Card | `#0D2640` / `#163352` |
| Border | `#0F2A42` / `#1A3F5C` |
| Destaque dourado | `#C8A24A` |
| Azul claro (eyebrows/ícones) | `#4A9EBF` |
| Vermelho (dor) | `#EF4444` |
| Texto principal | `#F8FAFC` |
| Texto secundário | `#CBD5E1` |
| Texto terciário | `#7A9BB5` |
| Fonte título | Barlow Condensed 900, caixa-alta |
| Fonte corpo | Inter |
| Botão CTA | gradiente navy `#1A4F72 → #123A5A → #0D2E45` |

**Não** usa o verde (#22c55e) da LP atual do curso.

---

## Oferta

| Campo | Valor |
|---|---|
| De | R$ 1.997,00 (riscado) |
| Por | **R$ 997,00** |
| Condição | Especial para participantes do Cemitério de Softwares |
| Prazo | Sem prazo definido na página |
| Parcelamento | Não exibido (visível no checkout) |
| Checkout URL | `https://checkout.squadhub.com.br/checkout/lp-monday-webinar` (placeholder) |
| Garantia | 30 dias incondicional |

---

## Estrutura de blocos (Abordagem B — 12 Blocos PVP adaptados para público quente)

### Bloco 1 — HERO / Headline de Promessa
- Eyebrow: badge "Condição Especial · Cemitério de Softwares"
- Headline principal (Barlow Condensed, grande): promessa de resultado direto — reduzir carga operacional, tirar do caos, centralizar tudo
- Sub-headline: complemento sem citar ferramenta — "o próximo passo do que você viu na aula"
- Botão CTA âncora (scroll para oferta)

### Bloco 2 — PONTE (dor comprimida + virada)
- Eyebrow: "Você reconhece esse cenário"
- 6 cards compactos de dor (reaproveitados do cemiterio.html: WhatsApp virou CRM, planilha desatualizada, assinaturas que não entregam, retrabalho, você é o gargalo, mais software mais confusão)
- Frase de virada: "No webinar você viu o diagnóstico. Aqui está o tratamento."
- Botão âncora secundário

### Bloco 3 — PROVAS (depoimentos + autoridade)
- Header: "O que dizem quem já aplicou o método"
- 3 depoimentos: Lucas Ampessan (agência), Vanessa Esquivel (Mr. Cat), Bartolomeu Junior (Hoom Interativa)
- Faixa de autoridade SquadHub (250+ empresas / 33k+ alunos / 6+ anos / Parceira Oficial Monday.com) — sem bio individual do Eduardo

### Bloco 4 — HEADLINE + BULLETS DE DESEJO
- Nova manchete focada no estado futuro desejado (autonomia do time, clareza macrogerencial, escalar sem contratar)
- 5 bullets de desejo ligados aos 4 temas do webinar (por que softwares falham, mapear o que precisa, IA na gestão, escalar com menos)

### Bloco 5 — EXCLUSIVIDADE (3-5 problemas detalhados)
- Headline: "Seus resultados indicam que você pode estar enfrentando:"
- 3-5 problemas com 1 parágrafo cada (versão expandida dos cards do Bloco 2)

### Bloco 6 — DOR & SOLUÇÃO (3 entregas como pares)
- Headline: promessa direta ("Elimine tudo isso com a Formação em Monday")
- 3 pares dor→solução: Curso sob a ótica do dono / IA e Automações / Painel do CEO

### Bloco 7 — COMO FUNCIONA (3 passos)
- Passo 1: Mapear (aprender a estrutura)
- Passo 2: Implementar (templates prontos, copiar e colar)
- Passo 3: Automatizar e monitorar (IA + Painel CEO)
- Cada passo com benefício concreto

### Bloco 8 — ENTREGÁVEIS
- Headline: "O que você leva ao garantir acesso hoje"
- Descrição da formação completa + IA + Painel
- Grid 3 cards igual à LP atual

### Bloco 9 — BÔNUS + VANTAGENS
- Headline: "Você ainda leva +R$2.300 em bônus exclusivos de graça"
- Bônus 1: Templates Validados SquadHub (R$497 grátis)
- Bônus 2: Curso Express Scrum para Negócios (R$797 grátis)
- Bônus 3: Diagnóstico Estratégico Individual 30min (R$997 grátis)
- 6-8 bullets de vantagens

### Bloco 10 — OFERTA IRRESISTÍVEL
- Ancoragem: "Somando tudo, o valor real passaria de R$3.000"
- Destaque visual: **De R$1.997 por R$997**
- Condição especial de participante do Cemitério de Softwares
- CTA principal
- Suporte: "Acesso imediato · Templates inclusos · 30 dias de garantia"

### Bloco 11 — GARANTIA
- Risco Zero 30 dias incondicional
- Ícone escudo + texto reaproveitado da LP atual

### Bloco 12 — FAQ + FOOTER
- 5 perguntas (FAQ da LP atual, adaptando a Q1 para citar o webinar como contexto)
- Rodapé legal

---

## Técnico

- HTML único e autocontido (sem frameworks externos além das Google Fonts)
- Sem vídeo, sem formulário, sem modal
- Scroll suave nos botões de âncora
- Responsivo: mobile-first, breakpoints em 520px e 760px
- Sem base64 embutido (sem imagens pesadas)
- Placeholder de checkout claramente comentado no HTML

---

## Restrições de conteúdo

- ✅ Pode mencionar Monday.com (produto sendo vendido)
- ❌ Não mencionar Leonardo Adonis (não participa do webinar/evento)
- ❌ Não mencionar preço de parcelamento na página
- ❌ Não apresentar bio/foto do Eduardo Leal (público já o conhece)
