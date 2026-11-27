# ChiriDevFlow IA

Dashboard locale di IlChiriDev per organizzare lo sviluppo dei videogiochi dal briefing alla pubblicazione. Raccoglie concept, artwork, asset, modelli 3D, animazioni e attività di progetto.

**[Scarica ChiriDevFlow IA per Windows x64](./Game-Dashboard-Windows-x64.zip?raw=true)**

**[Scarica ChiriDevFlow IA per macOS](./Game-Dashboard-macOS.zip?raw=true)**

## Installazione su Windows

1. Scarica ed estrai lo ZIP in una cartella scrivibile, per esempio «Documenti».
2. Apri la cartella «Game Dashboard» e fai doppio clic su **Avvia-dashboard.cmd**. Il launcher usa il PHP incluso e apre la dashboard nel browser.
3. Seleziona **Nuovo progetto**. Puoi creare una cartella di lavoro oppure collegarne una esistente.

Il primo avvio crea un registro vuoto nel file «var/workflow.sqlite». Le schede e gli allegati caricati sono locali. I file collegati restano nelle loro cartelle originali. Per arrestare il server fai doppio clic su **Arresta-dashboard.cmd**.

Se Windows segnala che manca il runtime Visual C++ v14, installa la [versione x64 dal sito Microsoft](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist/) e riapri il launcher.

## Installazione su macOS

1. Serve PHP 8.2 o successivo con PDO SQLite, mbstring e fileinfo. Se lo hai già, passa al punto 2.
   - **Apple Silicon con macOS supportato da Homebrew**. Configura [Homebrew](https://docs.brew.sh/Installation) e lancia `brew install php` nel Terminale.
   - **Intel o macOS fuori dal supporto di Homebrew**. Installa [MacPorts](https://www.macports.org/install.php) per la tua versione di macOS e lancia `sudo port install php84 php84-sqlite php84-mbstring`.
2. Scarica ed estrai lo ZIP macOS in una cartella scrivibile, per esempio «Documenti».
3. Apri **Terminale**, scrivi `bash` seguito da uno spazio, trascina **Avvia-dashboard.command** dalla cartella «Game Dashboard» nella finestra e premi Invio.
4. La dashboard si apre nel browser predefinito. Usa Safari 15.4 o successivo oppure un altro browser aggiornato. Tieni aperto il Terminale e premi **Ctrl+C** per arrestarla.

Il primo avvio crea il registro locale in `var/workflow.sqlite`. Per collegare un gioco, copia il percorso della cartella dal Finder. Fai clic destro sulla cartella, tieni premuto **⌥ Opzione** e scegli **Copia come percorso**.

## Connessioni IA e skill

Sotto **Impostazioni → Connessioni IA** trovi i comandi per collegare il registro in sola lettura a Codex, Claude Code o a un altro client compatibile con MCP su stdio. In **Impostazioni → Skill** trovi le quattro procedure scaricabili e le istruzioni da copiare nel tuo assistente IA.

## Licenza

Il codice, la documentazione, le quattro skill e la grafica originali di ChiriDevFlow IA sono distribuiti con licenza **0BSD**. Puoi usarli, copiarli, modificarli e ridistribuirli anche per scopi commerciali, senza obbligo di attribuzione.

PHP e i componenti di terze parti mantengono le proprie licenze. Gli avvisi del PHP incluso per Windows sono nella cartella «runtime/php» del relativo ZIP.

<details>
<summary>Testo della licenza 0BSD</summary>

~~~text
Copyright (C) 2026 IlChiriDev

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
~~~

</details>
