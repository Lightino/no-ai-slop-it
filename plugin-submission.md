# Presentazione del plugin No AI Slop IT

## Descrizione

No AI Slop IT è la versione italiana della skill di Peter Yang. Elimina oltre 20 pattern che rendono generica la scrittura assistita dall'AI, preservando la voce dell'autore.

## Prompt iniziali

1. @No AI Slop IT (testo)
2. @No AI Slop IT ci sono pattern da AI? (testo)

## Casi di prova positivi

1. Modificare un'email grezza con preamboli inutili, un contrasto binario e un finale pseudo-profondo. Preservare il tono schietto dell'autore e restituire il testo completo con la sezione **Cosa è cambiato**.
2. Analizzare un post LinkedIn senza riscriverlo. Indicare ogni pattern, citare la frase interessata e suggerire una breve correzione.
3. Modificare un saggio personale con umorismo e digressioni. Eliminare solo i veri pattern artificiali e mantenere la personalità.
4. Modificare un aggiornamento di prodotto che contiene numeri concreti. Preservare ogni fatto supportato e rendere i verbi più diretti.
5. Modificare una lunga bozza dal ritmo parlato. Districare le frasi davvero confuse mantenendo la cadenza naturale.

## Casi di prova negativi

1. L'utente fa una domanda fattuale senza condividere un testo. Non avviare la procedura di editing.
2. L'utente chiede se un passaggio è stato scritto da un'AI. Non tentare di indovinarlo; proporre un'analisi dei pattern.
3. L'utente chiede di inventare fatti o fonti a sostegno del testo. Non inventarli; chiedere prove oppure omettere l'affermazione.

## Note di versione

La versione 1.0.7 completa la traduzione italiana delle istruzioni, dei controlli e dei metadati. Il nome della skill e del pacchetto è `no-ai-slop-it`. Il plugin comprende le modalità di modifica e rilevamento, preserva la voce dell'autore e non richiede server esterni o autenticazione.
