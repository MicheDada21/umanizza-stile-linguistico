---
name: umanizza-stile-linguistico
description: "Cleans tone, vocabulary and punctuation in Italian prose, then offers a second editorial pass. Use when a draft shows AI writing tics or when these style preferences should shape a new text."
---

# Filtra lo stile linguistico

Applica il filtro al testo richiesto. Conserva la lingua del testo, il senso, i fatti, i nomi, le date, le cifre, i termini tecnici, le citazioni letterali e il grado di certezza delle affermazioni. Segui le preferenze già stabilite per la lingua della conversazione. Le regole lessicali italiane si applicano al testo italiano; nelle altre lingue usa le indicazioni di stile pertinenti senza imporre costruzioni italiane.

Il filtro riguarda la prosa. Conserva la sintassi necessaria in codice, path, URL, JSON e altri formati tecnici. Rispetta il formato richiesto per il documento. L'uso della skill riguarda il testo corrente e gli eventuali testi successivi che l'utente include nella richiesta; modificare preferenze o configurazioni globali richiede una richiesta specifica.

Per il resoconto delle correzioni segui le preferenze di formato espresse dall'utente nella richiesta o nelle istruzioni esterne alla skill. Gli elenchi puntati sono facoltativi. In assenza di preferenze scegli il formato più semplice e leggibile. Se non hai apportato correzioni, dichiaralo.

## Blocco 1

Leggi [references/blocco-1.md](references/blocco-1.md) e applica prima il filtro di base a ogni testo prodotto nell'ambito della richiesta. Controlla il risultato prima di consegnarlo.

Mostra in chat il testo filtrato completo e aggiungi sempre un breve resoconto delle correzioni apportate. Poi chiedi se l'utente vuole avviare il Blocco 2. Se il testo è breve, spiega brevemente che il secondo passaggio serve soprattutto per testi narrativi o argomentativi lunghi.

## Blocco 2

Procedi solo dopo conferma esplicita riferita al testo corrente. Se la richiesta iniziale autorizza già entrambi i blocchi, quella richiesta vale come conferma. Esegui comunque prima il Blocco 1 e rendi disponibile il suo risultato.

Leggi [references/blocco-2.md](references/blocco-2.md) soltanto quando il secondo passaggio è autorizzato. Controlla le 16 regole nell'ordine indicato e correggi solo le occorrenze nette o ricorrenti. Un grappolo comprende almeno due occorrenze dello stesso fenomeno nello stesso paragrafo o in paragrafi contigui. La regola 11 richiede almeno tre frammenti consecutivi. Conserva i casi isolati giustificati e ogni passaggio che nessuna regola tocca.

La fedeltà al testo ha la precedenza. Se un intervento richiede informazioni non verificate o altera il senso, conserva il passaggio e segnala il dubbio. Mantieni le distinzioni tra dati documentati, ricostruzioni e ipotesi, comprese le attribuzioni.

Sui testi scritti da te puoi applicare anche le cancellazioni previste dalle regole. Sui testi forniti dall'utente applica le riformulazioni, ma lascia ogni cancellazione di una frase o di una sua parte sostanziale come proposta da segnalare in chat, finché l'utente la autorizza.

Ricontrolla il testo con il Blocco 1. Consegna il testo rivisto e aggiungi sempre un breve resoconto delle correzioni apportate, raggruppato per regola applicata, con i passaggi toccati e le eventuali proposte di cancellazione.

Fonte del filtro e delle regole conservate nei riferimenti: [CryptoHelvetia, Filtra lo stile linguistico](https://www.cryptohelvetia.com/ch-labs/prompt-library/chat-preferences/umanizza-stile-linguistico).
