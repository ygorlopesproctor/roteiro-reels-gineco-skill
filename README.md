# roteiro-reels-gineco

Skill (Claude Code) da **MadScale / Black Sales** que gera o **roteiro completo de um reel de ginecologia** modelando *estritamente* a fórmula viral da **Dra. Nayara Alcântara** (@dranayara_alcantara — 8,3 milhões de views no top 20). Você passa um tema/dor; a skill devolve o pacote pronto pra gravar — e roda um **loop de auditoria** antes de entregar.

> **Não é** um gerador genérico de conteúdo. É a engenharia reversa de uma fórmula comprovada, aplicada à voz e ao posicionamento de cada médica, sob filtro **CFM**.

## O que ela entrega (por reel)
Um **pacote completo**:
- 🎙️ **ROTEIRO** — a fala palavra-por-palavra nos **7 blocos** da anatomia.
- 🖼️ **CAPA** — estilo + headline + b-roll do topo + direção do frame.
- ✍️ **LEGENDA** — emoji-alerta + gancho + CTAs em camadas.

## A anatomia (7 blocos)
`[01]` gancho de autoridade + quebra (4 arquétipos, incl. **alvo adjacente** mãe/marido) → `[02]` inimigo/reframe ("não é X, é Y") → `[03]` CTA cedo com porquê → `[04]` lista numerada + **mecanismo fisiológico obrigatório** → `[05]` CTA de retenção no meio → `[06]` bordão citável → `[07]` **assinatura no fim** + CTA. Detalhe em [`references/metodologia-nayara.md`](references/metodologia-nayara.md).

## Como funciona
1. **Entrevista curta** — tema · médica/posicionamento · **estágio de funil** (topo/meio/fundo) · modo venda · nº de rodadas.
2. **Diagnóstico de consciência** (via Núcleo de Copy) trava o gancho pelo tipo de lead — nunca por intuição.
3. **Roteirista** escreve o pacote seguindo a fórmula.
4. **Loop de 4 auditores independentes** (contexto isolado, veredicto binário APROVADO/REPROVADO) — **Fidelidade à fórmula · Clínico/CFM · Viralização · Núcleo de Copy** — repete até os 4 aprovarem ou bater o limite de rodadas (mesma dinâmica da skill `ciclo-design`).
5. **Entrega** só depois dos 4 APROVADO.

## Lastro (dado real, não achismo)
A skill se apoia em transcrições reais (WhisperX) de **três criadores da mesma escola** (mentor Elias Maman):
- **Nayara Alcântara** (ginecologia) — 18 roteiros · a *lei* da fórmula. `assets/transcricoes-brutas/`
- **Raianne Badiani** (peer) — 20 roteiros · motor de **compartilhamento** (= o motor do nicho médico). `assets/peer-raianne/`
- **Elias Maman** (mentor) — talking-heads · camada de funil/distribuição. `assets/mentor-elias/`

A [`references/cross-anatomia.md`](references/cross-anatomia.md) cruza os três e destila o **esqueleto invariante** + os 5 slots que trocam por nicho.

## Estrutura
```
SKILL.md                      # orquestração (entrevista → roteirista → loop → entrega)
references/
  metodologia-nayara.md       # a lei: 7 blocos, 4 arquétipos, DNA/tiques
  swipe-file.md               # 18 roteiros da Nayara destrinchados
  swipe-raianne.md            # 20 roteiros da Raianne destrinchados
  cross-anatomia.md           # Nayara × Elias × Raianne — o esqueleto invariante
  funil-e-consciencia.md      # eixo de funil + 3 consciências + playbooks Elias/Raianne
  capas.md · banco-de-dores.md · vies-de-vendas.md · checklist-cfm.md · loop-auditoria.md · nucleo-copy.md
assets/
  transcricoes-brutas/  capas-referencia/  onepager-anatomia.html
  peer-raianne/  mentor-elias/
```

## Uso
No Claude Code: `/roteiro-reels-gineco [tema] pra Dra. X, [modo venda], [N rodadas]`
Ex.: `/roteiro-reels-gineco coceira pós-menstruação pra Dra. Fulana, modo venda, 3 rodadas`

## Guarda-CFM
Topo de funil sempre. Nunca "agende consulta" no reel, promessa de resultado, diagnóstico fechado, antes/depois ou alarmismo. Ver [`references/checklist-cfm.md`](references/checklist-cfm.md).

---
Material proprietário MadScale / Black Sales. As transcrições e capas de terceiros são conteúdo público, usado como referência de análise/modelagem.
