# ChiriDevFlow IA

Dashboard locale di IlChiriDev per organizzare lo sviluppo dei videogiochi dal briefing alla pubblicazione. Raccoglie concept, artwork, asset, modelli 3D, animazioni e attività di progetto.

**[Scarica ChiriDevFlow IA per Windows x64](./Game-Dashboard-Windows-x64.zip?raw=true)**

## Installazione

1. Scarica ed estrai lo ZIP in una cartella scrivibile, per esempio «Documenti».
2. Apri la cartella «Game Dashboard» e fai doppio clic su **Avvia-dashboard.cmd**. Il launcher usa il PHP incluso e apre la dashboard nel browser.
3. Seleziona **Nuovo progetto**. Puoi creare una cartella di lavoro oppure collegarne una esistente.

Il primo avvio crea un registro vuoto nel file «var/workflow.sqlite». Le schede e gli allegati caricati sono locali. I file collegati restano nelle loro cartelle originali. Per arrestare il server fai doppio clic su **Arresta-dashboard.cmd**.

Se Windows segnala che manca il runtime Visual C++ v14, installa la [versione x64 dal sito Microsoft](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist/) e riapri il launcher.

## Connessioni IA e skill

Sotto **Impostazioni → Connessioni IA** trovi i comandi per collegare il registro in sola lettura a Codex, Claude Code o a un altro client compatibile con MCP su stdio. In **Impostazioni → Skill** trovi le quattro procedure scaricabili e le istruzioni da copiare nel tuo assistente IA.

## Licenza

Il codice, la documentazione, le quattro skill e la grafica originali di ChiriDevFlow IA sono distribuiti con licenza **0BSD**. Puoi usarli, copiarli, modificarli e ridistribuirli anche per scopi commerciali, senza obbligo di attribuzione.

PHP e i componenti di terze parti mantengono le proprie licenze. Gli avvisi di PHP sono nella cartella «runtime/php» dello ZIP.

<details>
<summary>Testo della licenza 0BSD</summary>

~~~text
Copyright (C) 2026 IlChiriDev

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
~~~

</details>
