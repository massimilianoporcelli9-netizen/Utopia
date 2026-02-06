# CinqueInContatto

Mini app web per un gruppo di 5 amici che vogliono restare in contatto.

## Come aprirla e farla funzionare

### Opzione 1 (consigliata): server locale
1. Apri un terminale nella cartella del progetto.
2. Avvia:
   ```bash
   python3 -m http.server 4173
   ```
3. Apri il browser su:
   `http://localhost:4173`
4. Ferma il server con `Ctrl+C`.

### Opzione 2: apertura diretta
Puoi anche aprire `index.html` con doppio click, ma alcune funzioni browser possono essere più affidabili con il server locale.

## Funzioni principali
- Bacheca messaggi condivisa (chat/eventi/task)
- Filtro per tipo + ricerca testuale
- Agenda con prossime scadenze
- Backup JSON
- Salvataggio automatico in `localStorage`
