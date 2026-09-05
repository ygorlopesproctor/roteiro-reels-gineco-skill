# Ponte pro Núcleo de Copy — o motor que esta skill roda (v2.0)

> **Fonte única:** o núcleo vive em `Copy/_nucleo/` (na raiz do projeto "PROJETO 2"). Este arquivo NÃO copia o conteúdo de lá — ele aponta o que ler, em que ordem, e como cada estágio se encaixa NESTA skill. Se este arquivo e o núcleo divergirem, **o núcleo manda**.

**Resultado pro médico (o porquê disto tudo):** o reel não existe pra dar view — existe pra virar **levantada de mão** que alimenta o funil (comentário qualificado → DM/automação → WhatsApp → agenda). View é meio; identificação + salvamento + comentário qualificado é o que move paciente pro consultório.

---

## Os estágios que ESTA skill roda (nesta ordem)

| Ordem | Arquivo do núcleo | O que decide no reel | Quando roda no pipeline |
|---|---|---|---|
| 1º | `Copy/_nucleo/_CONTEXTO-OPERACAO.md` + `00-filtro-cfm.md` | a língua da operação + o gate (o que nunca sai) | leitura antes de tudo |
| 2º | `Copy/_nucleo/01-diagnostico-consciencia.md` | **o GANCHO** — nível de consciência + sofisticação → **tipo de lead travado** → arquétipo A/B/C/D | Passo 1 do pipeline (rodar o 🔧 BLOCO PROMPTÁVEL) |
| 3º | `Copy/_nucleo/04-headlines-e-balas.md` | **as frases** — gancho falado + headline da capa (mesmo gerador, regra 7×, trava CFM) + itens do corpo com 3º degrau da bala | Passo 2 (Roteirista) |
| 4º | `Copy/_nucleo/05-prova-e-emocao.md` | **fazer acreditar** — dado nunca cru (ABT), emoção só por indireção, respaldo real | Passo 2 (Roteirista) |
| 5º | `Copy/_nucleo/00-filtro-cfm.md` (de novo) | QA final + swap CFM antes de entregar | antes da entrega (além do Auditor 2) |

Em cada arquivo `NN`, execute a seção **🔧 BLOCO PROMPTÁVEL** — o resto é referência.

## Como o estágio 01 trava o gancho (o fim da intuição)

Rode o BLOCO PROMPTÁVEL do `01` com os inputs: `publico=paciente` · `peca=reel` · `origem_trafego=social frio` · `especialidade=ginecologia` · posicionamento + alto ticket da médica (da entrevista). Cole o bloco `DIAGNÓSTICO` no topo do pacote. **Nenhuma linha de roteiro antes disso.**

O tipo de lead travado no 01 escolhe o arquétipo de gancho Nayara (o arquétipo é a EXECUÇÃO do lead na estética dela — a fórmula dos 7 blocos não muda):

| Lead travado (estágio 01) | Arquétipo de gancho (metodologia-nayara.md) |
|---|---|
| **Problema-Solução** (nível 4 — o padrão do reel) | **A** (erro/alerta que dramatiza o problema) ou **B** (pergunta na voz da paciente) |
| **Grande Segredo** (nível 4-5) | **B** ("o que ninguém te conta") ou **A** |
| **Revelação** (nível 5 · fato que ela não sabia) | **B** (pergunta/mito do consultório) |
| **História/Identificação** (nível 5 · sofisticação 5 — mercado em fadiga) | **C** (alvo adjacente) ou **D** (analogia visceral) |
| **Promessa** (nível 3 — só em modo venda, roteiro QUENTE) | **A com número contável** ("3 sinais…") — promessa de ENTENDIMENTO, nunca clínica |
| **Oferta** (nível 1) | ❌ não existe em reel — reel é topo de funil, sempre |

Lembretes do 01 que valem dobrado aqui: sofisticação ≥3 → mecanismo nomeado, nunca promessa maior · sofisticação 5 (menopausa, emagrecimento) → força identificação (C/D) · alvo adjacente (mãe/marido) conta como identificação e multiplica alcance.

## Como o 04 e o 05 entram no Roteirista

- **04 · gancho e capa:** o gancho é uma bala classe A dita em voz alta — gere o estoque (regra 7×, calibrado FRIO: sintoma/erro/mito, nunca apresentação), passe a **trava CFM** do 04 (lista proibida), aplique o Makeover nas melhores e entregue 3 variações ≤12 palavras faladas como se fala. A headline da capa sai do MESMO estoque (a capa é o gancho escrito — `capas.md`). Itens do corpo: feche cada um com o 3º degrau da bala na voz da paciente ("o que significa que…" → rotina recuperada/fim da incerteza, jamais desfecho clínico).
- **05 · prova e emoção:** todo número/estatística/respaldo entra embrulhado (ABT: E→MAS→PORTANTO) — dado cru anestesia. O bloco [02] inimigo/dor é emoção por **indireção**: cena vivida que só quem sente reconhece; quem nomeia a dor é a paciente, nunca a copy. Respaldo citado é real ou não entra.

## O que o Auditor 4 (Núcleo) cobra

Este arquivo + os estágios acima são o briefing do **Auditor 4 · Núcleo** no `loop-auditoria.md`. Ele reprova o pacote que ignorou o motor: gancho sem lead travado (sem bloco `DIAGNÓSTICO`), promessa de resultado/claim ampliado, dado cru fora de ABT, emoção nomeada pela copy, ou pacote sem rota de levantada de mão.
