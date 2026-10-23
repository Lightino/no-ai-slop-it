# No AI Slop IT

Elimina oltre 20 pattern tipici della scrittura generata dall'intelligenza artificiale senza appiattire la tua voce personale.

https://github.com/user-attachments/assets/f3055450-78eb-4672-880a-88a4fa54bde9

## Il problema

L'AI rende facile generare testi formalmente corretti, ma che finiscono per assomigliarsi tutti. Anche i modelli migliori continuano a produrre frasi come:

- «Non è X. È Y.»
- «Quello che nessuno ti dice è…»
- «Il futuro non sta arrivando. È già qui.»

Quando usi l'AI per modificare un testo, rischi anche di perdere il vocabolario, il ritmo, l'umorismo e le imperfezioni che rendono riconoscibile il tuo modo di scrivere.

## Come installare No AI Slop IT

Il modo più semplice per installare la skill è incollare questa istruzione in ChatGPT, Claude Code, Codex o nel tuo agente di programmazione preferito:

```text
Installa globalmente la skill /no-ai-slop-it da https://github.com/lightino/no-ai-slop-it
```

Puoi anche installarla tramite `npx`:

```sh
npx skills add lightino/no-ai-slop-it --skill no-ai-slop-it --global --yes
```

## Come usare No AI Slop IT

### Modificare un testo

```text
/no-ai-slop-it (il tuo testo)
```

La skill elimina i pattern tipici della scrittura artificiale, preserva la tua voce personale ed elenca le modifiche effettuate.

### Individuare i pattern artificiali

```text
/no-ai-slop-it ci sono pattern da AI? (il tuo testo)
```

La skill cita ogni pattern problematico individuato, senza cercare di indovinare se il testo sia stato scritto da un'AI.

### Generare testi artificiali per divertimento

```text
Scrivi un post volutamente pieno di AI slop su (argomento)
```

Puoi utilizzare la skill anche per generare, a scopo satirico, testi esasperatamente artificiali, pieni di cliché e formule stereotipate.

## I pattern che questa skill riconosce

No AI Slop IT controlla oltre 20 pattern, tra cui:

1. **Contrasti binari.** «Non è X. È Y.»
2. **Preamboli inutili.** «Il punto è questo», «Voglio essere chiaro».
3. **Introduzioni da falsa rivelazione.** «Quello che nessuno ti dice», «La parte che sfugge a tutti».
4. **Rivelazioni dopo i due punti.** «La parte migliore: impara.»
5. **Frammentazione drammatica.** «È tutto. È davvero tutto.»
6. **Analisi superficiale.** «Sottolineando l'impegno del team verso l'innovazione».
7. **Enfasi artificiale sull'importanza.** «Segna un momento cruciale», «è una testimonianza di».
8. **Attribuzioni vaghe.** «Gli esperti concordano», «gli studi dimostrano».
9. **Rotazione dei sinonimi.** «L'agente gestisce le tue email. L'assistente prepara le risposte».
10. **Finali pseudo-profondi.** «Il futuro non sta arrivando. È già qui.»

La skill controlla anche i principi fondamentali della buona scrittura: andare subito al punto quando è utile, preferire la forma attiva, semplificare le frasi difficili da seguire e privilegiare dettagli concreti rispetto alle astrazioni.

## Cosa contiene

- [`SKILL.md`](https://github.com/lightino/no-ai-slop-it/blob/main/skills/no-ai-slop-it/SKILL.md) contiene le regole di editing e la procedura operativa.
- [`eval.md`](https://github.com/lightino/no-ai-slop-it/blob/main/skills/no-ai-slop-it/eval.md) contiene i controlli che la skill esegue sul proprio lavoro.
- [`.codex-plugin/plugin.json`](https://github.com/lightino/no-ai-slop-it/blob/main/.codex-plugin/plugin.json) contiene i metadati del plugin per ChatGPT e Codex.
- [`build_plugin.py`](https://github.com/lightino/no-ai-slop-it/blob/main/scripts/build_plugin.py) crea e convalida il pacchetto del plugin.

Il repository include i metadati e lo script per creare il pacchetto del plugin.

Per convalidarlo senza conservare il pacchetto generato:

```sh
python scripts/build_plugin.py --check
```

## Crediti

Traduzione e adattamento italiano a cura di [Lightino](https://github.com/Lightino), basati su [No AI Slop di Peter Yang](https://github.com/petergyang/no-ai-slop). La licenza e il copyright originali sono conservati nel file [LICENSE](LICENSE).

## Licenza

MIT
