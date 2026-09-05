---
name: roteiro-reels-gineco
description: Use SEMPRE que a equipe MadScale/Black Sales precisar gerar o ROTEIRO de um reel de ginecologia pra uma médica-cliente (ou prospect), modelando ESTRITAMENTE a fórmula viral da Dra. Nayara Alcântara (@dranayara_alcantara · 8,3 MI de views no top 20). Gatilhos — "roteiro de reel pra Dra. X sobre [tema]", "gera um reel de [tema] no padrão Nayara", "roteiro de conteúdo gineco", "/roteiro-reels-gineco [tema]", "escreve um reel sobre [dor] pra [médica]", ou quando o usuário passa um tema/dor de ginecologia pedindo o roteiro pronto. Entrega o PACOTE COMPLETO por reel (roteiro palavra-por-palavra nos 7 blocos + direção de capa + legenda com CTAs), e roda um LOOP de auditoria (Roteirista + 4 auditores independentes: Fidelidade à fórmula · Clínico/CFM · Viralização · Núcleo de Copy) até todos aprovarem ou bater o limite de rodadas que o usuário definir — mesma dinâmica da skill ciclo-design. NÃO confundir com `plano-de-acao` (a apresentação de vendas 90d, que usa esta fórmula na parte de conteúdo) nem com `copy-lp-medico` (copy de landing page).
version: 2.2.0
engine: Claude Opus 4.8 · loop Roteirista + 4 auditores (modelo ciclo-design) · lastro nas 20 transcrições reais · motor de copy do núcleo (Copy/_nucleo/) · eixo de funil + 3 consciências + playbook do mentor Elias + peer Raianne
changelog: 2.2.0 — playbook da peer Raianne Badiani (aluna do mesmo mentor · top 20 mapeado + 4 transcrições · movida a COMPARTILHAMENTO TRIBAL = o motor do nicho médico) somado ao `funil-e-consciencia.md` (bloco D): 10 mecânicas novas de copy CFM-safe (loop do último item no gancho · bloco-sanduíche no meio · alerta ao grupo nomeado · newsjacking/pivô de celebridade · prova bruta intercalada · espelhamento em escada · palavra-chave-manifesto · fecho circular · aforismos em rajada · assinatura de missão + metáfora proprietária) + prova empírica CTA↔KPI. Confirma a anatomia de 7 blocos como lei; Raianne = variações de posição + mecânicas. Dados em `assets/peer-raianne/`. | 2.1.0 — eixo de FUNIL (topo/meio/fundo) na entrevista + premissa das 3 CONSCIÊNCIAS (problema/solução/doutora) como objetivo fixo de todo reel + playbook do mentor Elias Maman (pergunta que convida opinião · palavra-chave→DM · corte de convidado · arco de transformação, tudo CFM-safe) mapeado do top 20 dele; tudo em `references/funil-e-consciencia.md`. Modula ângulo/arquétipo/CTA/formato — a anatomia de 7 blocos e o núcleo continuam intactos. | 2.0.0 — plugada no Núcleo de Copy (Copy/_nucleo/ · estágios 00·01·04·05) — gancho travado pelo diagnóstico de consciência (01) em vez de intuição, balas/ganchos pelo gerador do 04, prova/emoção por indireção do 05, e 4º auditor "Núcleo" SOMADO ao loop (os 3 originais permanecem); fórmula Nayara 100% intacta.
---

# Roteiro de Reels · fórmula Nayara Alcântara (ginecologia)

> Gera roteiros de reel que seguem **estritamente** a anatomia dos conteúdos que fizeram a Dra. Nayara Alcântara viralizar (8,3 milhões de views no top 20 · 18 roteiros, 1 fórmula). Nada genérico, nada abrangente: modela a **estrutura e a voz** dela e adapta ao posicionamento da médica-cliente. Cada roteiro passa por um **loop de 4 auditores independentes** antes de ser entregue.

> ⚠️ **Não é sobre copiar o tema dela — é sobre replicar a MÁQUINA.** O usuário passa o tema; a skill aplica a fórmula. Ver `references/metodologia-nayara.md` (a lei) e `references/swipe-file.md` (os roteiros reais destrinchados).

## Lastro (verificação de base — não pular)
A skill se apoia nas **20 transcrições reais** dos reels de maior alcance dela, transcritas via WhisperX e guardadas em `assets/transcricoes-brutas/01..20.txt` (18 roteiros únicos; 01=05 e 13=15 são reposts). As capas de referência estão em `assets/capas-referencia/`. Antes de gerar, confirme que esses arquivos existem — são a matéria-prima. Se faltar, avise; **nunca invente a fórmula.**

---

## Quando disparar
Qualquer pedido de roteiro de reel de ginecologia: "roteiro pra Dra. X sobre [tema]", "reel de [dor] no padrão Nayara", "/roteiro-reels-gineco [tema]". Se vier só o tema, siga a entrevista curta abaixo.

## Entrevista curta (faça junto, depois pare e espere)
Pergunte só o que muda o resultado:

1. **Qual o tema/dor do reel?** (ex.: "coceira depois da menstruação", "incontinência depois dos 40"). Aceita 1 ou vários.
2. **Pra qual médica? Qual o posicionamento e a voz dela?** (nome + como ela quer ser vista + alto ticket que ela vende). Se não houver, uso o posicionamento-padrão gineco e aviso — mas sem isso o Auditor de Fidelidade fica sem régua (ver `loop-auditoria.md`).
3. 🆕 **Estágio de funil?** (ver `references/funil-e-consciencia.md`):
   - **TOPO** — alcance, abrangente, pra mais gente (dor cotidiana ampla · CTA comentar/compartilhar).
   - **MEIO** — específico/denso/técnico; escolher o sub-tipo: **autoridade** · **prova social** · **estudo de caso** · **corte de convidado** (CTA seguir/salvar).
   - **FUNDO** — focado em conversão / levantada de mão (CTA palavra-chave → DM).
   Se não disser, sugiro pelo tema e confirmo. **Premissa fixa (não muda):** todo reel eleva 3 consciências — do **problema**, da **solução** e da **doutora**; me diga se quer priorizar uma (senão eu escolho a coerente com o estágio de funil).
4. **Modo venda?** Sim = otimizo com viés comercial puxando pro alto ticket dela (`references/vies-de-vendas.md`), sem quebrar CFM/topo-de-funil. Não = puro alcance/autoridade (como a Nayara faz).
5. **Quantas rodadas máximas de auditoria?** (o ciclo para quando os 4 auditores aprovam ou bate esse limite). Sugestão: 3.
6. *(Opcional)* **Modelos por papel** — Roteirista, e os 4 auditores. Default: mesmo modelo forte pros cinco (qualidade > custo, porque o Ygor não quer volta).

Confirme em 1 bloco (tema · médica/posicionamento · **funil + consciência-alvo** · modo venda · máx rodadas) e siga.

---

## Núcleo de Copy (obrigatório · desde a v2.0)
Esta skill roda em cima do motor de copy da operação (`Copy/_nucleo/` na raiz do projeto). Antes de escrever qualquer roteiro:
1. Leia `references/nucleo-copy.md` — a ponte pro núcleo: aponta os estágios que ESTA skill roda, na ordem `00` (gate CFM) → `01` (diagnóstico de consciência → trava o GANCHO) → `04` (gerador de ganchos/balas) → `05` (prova & emoção por indireção) → `00` de novo como QA.
2. Execute o **🔧 BLOCO PROMPTÁVEL** de cada estágio no passo indicado do pipeline abaixo. O gancho **não é mais escolhido por intuição** — sai do tipo de lead travado no `01`.
3. Nunca reinvente princípio que o núcleo já define — puxe de lá.
4. Antes de entregar, passe o pacote no QA do `Copy/_nucleo/00-filtro-cfm.md` (além do Auditor 2).

**Resultado pro médico:** reel que vira **levantada de mão** (comentário qualificado → DM/WhatsApp → agenda), não só view.

---

## Pipeline

### 1. Ancoragem do tema + diagnóstico de consciência (estágio 01 do núcleo)
Ache o **pilar** do tema em `references/banco-de-dores.md` e o **alvo** (paciente ou alvo adjacente: mãe/marido). Puxe o(s) **mecanismo(s)** fisiológico(s) do pilar. Depois rode o 🔧 BLOCO PROMPTÁVEL de `Copy/_nucleo/01-diagnostico-consciencia.md` (inputs: `publico=paciente` · `peca=reel` · `origem=social frio` · posicionamento + alto ticket da médica) e cole o bloco `DIAGNÓSTICO` no topo do pacote. O **arquétipo de gancho (A/B/C/D) sai do tipo de lead travado** — matriz lead→arquétipo em `references/nucleo-copy.md`. O pilar recomenda; o DIAGNÓSTICO decide. 🆕 **v2.1 · trave também o FUNIL e a CONSCIÊNCIA-ALVO** (`references/funil-e-consciencia.md`): estágio de funil (topo/meio/fundo) + qual das 3 consciências este reel prioriza (problema/solução/doutora). Isso afina CTA (topo=comentar/compartilhar · meio=seguir/salvar · fundo=**palavra-chave→DM**), formato e ângulo — sem mudar a anatomia. Registre no bloco `DIAGNÓSTICO`.

### 2. Roteirista (Construtor) escreve o pacote completo
Seguindo `references/metodologia-nayara.md` À RISCA + modelando `references/swipe-file.md`, produz o **pacote** (formato de saída abaixo). Gancho falado e headline da capa saem do gerador do estágio `04` (estoque 7× calibrado FRIO + trava CFM + Makeover → 3 variações ≤12 palavras); cada item do corpo fecha no 3º degrau da bala na voz da paciente; números/respaldo entram embrulhados (ABT) e a emoção só por indireção (estágio `05`) — tudo em `references/nucleo-copy.md`. Se modo venda, aplica `references/vies-de-vendas.md`.

### 3. Loop de auditoria (Roteirista + 4 auditores independentes)
Rode o ciclo de `references/loop-auditoria.md`: os **4 auditores em paralelo, contexto novo, sem contaminação** — Fidelidade à fórmula · Clínico/CFM · Viralização · **Núcleo (motor de copy)**. Veredicto binário. Os 4 têm que aprovar. Reprovou → volta pro Roteirista com a MAIOR LACUNA. Repete até todos aprovarem ou bater o limite. Mantenha `progresso-roteiro.md`. **Bater o limite não vira aprovação** — se estourar com reprovação, pare e mostre a lacuna.

### 4. Entrega
Só entregue o pacote depois dos 4 APROVADO (ou com aviso explícito se o usuário mandou parar no limite). Diga em quantas rodadas fechou.

---

## Formato de saída (o PACOTE por reel)

Entregue assim (fala completa palavra-por-palavra — **nunca** tabela tempo/ação resumida):

```
🎬 REEL · [TEMA] · Dra. [NOME]
Pilar: [pilar] · Gancho: [arquétipo A/B/C/D] · Alvo: [paciente/mãe/marido] · Modo: [alcance/venda]
DIAGNÓSTICO (estágio 01): nível [N] · sofisticação [N] · lead travado: [tipo] → arquétipo [A/B/C/D]
Funil: [topo/meio/fundo] · Consciência-alvo: [problema/solução/doutora] · CTA: [comentar/compartilhar | seguir/salvar | palavra-chave→DM]

━━━ ROTEIRO (fala) ━━━
[01] GANCHO ................ <fala>
[02] INIMIGO/REFRAME ...... <fala>
[03] CTA CEDO ............. <fala>
[04] CORPO (lista+mecanismo)
   • Item 1 — <nome> → <mecanismo fisiológico> → <consequência> → <o que fazer>
   • Item 2 — ...
   [05] CTA RETENÇÃO ...... <fala, antes do último item>
   • Item 3 — ...
[06] BORDÃO ............... <frase "não é X, é Y">
[07] ASSINATURA + CTA FINAL <bio da médica + seguir/comentar/compartilhar com porquê>

━━━ CAPA ━━━
Estilo: [bloco caixa-alta / frase minúscula]
Headline: <1-2 linhas>
Topo (b-roll): <o que mostrar>
Base (frame dela): <enquadramento + cenário + expressão>

━━━ LEGENDA ━━━
<emoji-alerta + gancho que ecoa a capa + amplificação/mecanismo + CTAs em camadas: assistir→salvar→marcar→comentar>
```

Se o usuário pediu vários temas ou "2 roteiros", gere um pacote por tema. Em contexto de venda com 2 roteiros, varie a **temperatura** (1 FRIO/alcance + 1 QUENTE/desejo) conforme `references/vies-de-vendas.md`.

---

## Arquivos de referência
| Arquivo | Conteúdo |
|---|---|
| `references/metodologia-nayara.md` | **A lei** — os 7 blocos, 4 arquétipos de gancho, DNA/tiques, alvo adjacente, o que nunca fazer |
| `references/swipe-file.md` | Os 18 roteiros reais dela, limpos e destrinchados bloco a bloco + tabela-mapa |
| `references/capas.md` | Fórmula da capa (3 zonas + 2 estilos de headline) |
| `references/banco-de-dores.md` | 6 pilares gineco → arquétipo/alvo/mecanismo por pilar |
| `references/vies-de-vendas.md` | **Modo venda** — viés comercial CFM-safe (topo→alto ticket) |
| `references/checklist-cfm.md` | Guarda-freio CFM (bloqueante · briefing do Auditor 2) |
| `references/nucleo-copy.md` | **Ponte pro Núcleo de Copy** (`Copy/_nucleo/` · estágios 00·01·04·05 + matriz lead→gancho · briefing do Auditor 4) |
| 🆕 `references/funil-e-consciencia.md` | **v2.1-2.2** · eixo de FUNIL (topo/meio/fundo) + premissa das 3 CONSCIÊNCIAS (problema/solução/doutora) + playbook do mentor **Elias** (C) e da peer **Raianne** (D · 10 mecânicas CFM-safe) → modula ângulo/arquétipo/CTA/formato |
| `references/loop-auditoria.md` | O ciclo Roteirista + 4 auditores (modelo ciclo-design) |
| `assets/transcricoes-brutas/*.txt` | As 20 transcrições reais (lastro) |
| `assets/capas-referencia/*.jpg` | 6 capas reais de referência |
| `assets/onepager-anatomia.html` | One-pager que explica a anatomia (referência de estética; usado também na `plano-de-acao`) |
| 🆕 `assets/mentor-elias/` | Top 20 do mentor Elias Maman (mapa + JSON bruto) — lastro do playbook de funil/distribuição |
| 🆕 `assets/peer-raianne/` | Top 20 da peer Raianne Badiani (mapa + métricas + 4 transcrições + JSON) — lastro do bloco D |

## Regras inegociáveis (resumo)
- Segue os **7 blocos na ordem** (metodologia-nayara.md). Mecanismo fisiológico é **obrigatório**.
- **Assinatura no fim**, nunca no começo. CTA **sempre com porquê**. Alvo adjacente quando o tema pede.
- Escrito **como se fala**. **Específico, nunca genérico.** Modela a estrutura, **não copia o tema** da Nayara.
- Topo de funil (CFM). **Nunca "agende consulta"** no reel. Modo venda tilta o ângulo, não vira anúncio.
- O gancho nasce do **lead travado no estágio 01 do núcleo** (`references/nucleo-copy.md`) — nunca de intuição. Sem bloco DIAGNÓSTICO, não há roteiro.
- **Sempre** passa pelo loop de 4 auditores antes de entregar.
