# filtra-stile-linguistico

Ripulisce tono, lessico e punteggiatura di un testo in prosa e propone un secondo passaggio editoriale mirato.

Fa parte della [Prompt Library di CH Labs](https://www.cryptohelvetia.com/ch-labs/prompt-library), dove la pagina di riferimento è [Filtra lo stile linguistico](https://www.cryptohelvetia.com/ch-labs/prompt-library/chat-preferences/filtra-stile-linguistico). Il repo contiene una copia della skill, rigenerata a ogni aggiornamento della libreria.

## Installare

In Claude Code aggiungi una volta il marketplace e installa il plugin.

```
/plugin marketplace add MicheDada21/ch-labs-skills
/plugin install filtra-stile-linguistico@ch-labs-skills
```

Da shell i comandi sono `claude plugin marketplace add MicheDada21/ch-labs-skills` e `claude plugin install filtra-stile-linguistico@ch-labs-skills`. Nell'app desktop premi + accanto al campo del prompt, apri Plugins, aggiungi il marketplace `MicheDada21/ch-labs-skills` con Add marketplace e poi il plugin con Add plugin.

Per avere tutte le skill della libreria installa `tutte-le-skill@ch-labs-skills`. Con altri agenti copia la cartella `skills/filtra-stile-linguistico` tra le skill dell'agente, per esempio in `~/.codex/skills/filtra-stile-linguistico`.

## Licenza

MIT, testo completo in [LICENSE](LICENSE).
