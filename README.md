# Kitchen Controller — pacchetto PWA per iPad

Pubblica tutti questi file insieme **nella cartella principale** di un repository GitHub pubblico.
Non caricare lo ZIP su GitHub: estrailo prima e carica i singoli file.

## GitHub Pages
1. GitHub > New repository > nome suggerito `kitchen-controller` > **Public** > Create repository.
2. Nella scheda **Code**, scegli **Add file > Upload files** (se il repository è vuoto, puoi cliccare **uploading an existing file**). Trascina qui tutti i file estratti da questo ZIP, poi premi **Commit changes**.
3. Vai in **Settings > Pages** (menu laterale). In **Build and deployment**, imposta **Source: Deploy from a branch**, **Branch: main**, **Folder: /(root)** e **Save**.
4. Dopo alcuni minuti, apri l'indirizzo Pages indicato nella stessa schermata (esempio: `https://TUOUSERNAME.github.io/kitchen-controller/`).

## Installazione su iPad
1. Apri l'indirizzo GitHub Pages in **Safari**, con iPad connesso a Internet.
2. Tocca **Condividi** > **Aggiungi alla schermata Home** (se non lo vedi, scorri tra le azioni).
3. Mantieni attiva l'opzione **Apri come app Web**, se presente, e premi **Aggiungi**.
4. Apri l'icona **Kitchen Controller** dalla Home e usa l'iPad in orizzontale.

## Attenzione ai timer in cucina
- L'allarme sonoro dipende da volume, permessi e restrizioni Safari/iPadOS; **non è garantito a schermo spento o con l'app in background**.
- Per le cotture importanti mantieni iPad acceso, in primo piano e alimentato. Prova l'allarme con un countdown breve prima dell'uso.
- La modalità offline è disponibile **dopo la prima visita online** e dopo che il service worker ha installato la cache. Il sistema può cancellare la cache in certe condizioni.
- Timer, PIN e preferenze sono salvati **localmente sul singolo dispositivo/app**, non in cloud; reinstallazione, cancellazione dati o cambiamento di indirizzo possono azzerarli.
- Quando pubblichi nuove versioni dell'app, sostituisci `index.html` nello stesso repository; in caso di aggiornamento di altri file, incrementa la versione `CACHE_NAME` in `sw.js`.
