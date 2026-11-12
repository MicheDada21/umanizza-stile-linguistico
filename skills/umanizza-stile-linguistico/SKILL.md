---
name: umanizza-stile-linguistico
description: "Cleans tone, vocabulary and punctuation in Italian prose, then offers a second editorial pass. Use when a draft shows AI writing tics or when these style preferences should shape a new text."
---

# Umanizza stile linguistico

Il filtro si applica alla prosa italiana. Testi in altre lingue, codice, path, URL, JSON e altri formati tecnici passano invariati.

## Principi validi per entrambi i blocchi

La fedeltà al testo ha la precedenza sulle regole. Fatti, nomi, date, cifre, termini tecnici, citazioni letterali, vocabolario dell'autore e frasi che funzionano si conservano. Le distinzioni tra dato documentato, ricostruzione e ipotesi, insieme all'attribuzione di un'ipotesi al suo autore, sono informazione e rimangono intatte. Cita soltanto fonti già presenti nel testo o verificate. Quando una regola richiede di alterare il senso o di aggiungere informazioni non verificate, lascia il passaggio com'è e segnala il dubbio in chat.

Sui testi scritti da te applica ogni correzione, cancellazioni comprese. Sui testi dell'utente applica le riformulazioni e presenta in chat come proposta ogni cancellazione di una frase o di una sua parte sostanziale, finché l'utente la autorizza.

Ogni passata si chiude con una consegna, che comprende il testo completo, in chat oppure nel file in cui vive, e dopo di esso l'elenco completo delle modifiche. L'elenco segue l'ordine del testo e ha una riga per modifica, con il passaggio di partenza e la versione nuova. Contiene soltanto le modifiche, senza commenti, motivazioni o giudizi; i dubbi e le proposte di cancellazione vanno in chat dopo l'elenco, separati. Il formato segue le preferenze dell'utente quando ne ha espresse. Se non hai corretto niente, dichiaralo.

## Blocco 1

Leggi [references/blocco-1.md](references/blocco-1.md) e applicalo a ogni testo della richiesta. Il blocco è concluso quando il testo supera il controllo finale del file. Consegna il testo con l'elenco delle modifiche, poi chiedi se l'utente vuole il Blocco 2. Per un testo breve aggiungi che il Blocco 2 serve soprattutto a testi narrativi o argomentativi lunghi.

## Blocco 2

Parte solo dopo una conferma esplicita riferita al testo corrente; vale come conferma anche una richiesta iniziale che autorizza entrambi i blocchi. Il Blocco 1 viene comunque prima e il suo risultato va consegnato.

A quel punto leggi [references/blocco-2.md](references/blocco-2.md) e controlla ogni regola nell'ordine indicato. Il blocco è concluso quando tutte le regole sono state controllate e il testo rivisto supera di nuovo il controllo finale del Blocco 1. L'elenco raggruppa le modifiche per regola; le proposte di cancellazione lo seguono.

## Uso dentro un altro workflow

Quando un'altra skill chiama questo filtro, decide lei quando mostrare il risultato in chat e quando proporre il Blocco 2. Applica il blocco richiesto al testo indicato e restituisci il testo corretto con l'elenco delle modifiche, da includere nella consegna. Il chiamante può passare un profilo con termini ammessi, sostituzioni di dominio, nomi e citazioni da conservare e regole di formato. Il profilo prevale sul Blocco 1 per i casi che nomina; per tutto il resto valgono questo file e i suoi riferimenti.

La pagina pubblica del filtro è [CryptoHelvetia, Umanizza stile linguistico](https://www.cryptohelvetia.com/ch-labs/prompt-library/chat-preferences/umanizza-stile-linguistico).
