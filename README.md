Create due user control per gestire le giocate del PC e dell'utente

Purtroppo rimane il blocco sui file - **COME RISOLVERE**

**Aprire la powershell di windows**

Inserire il seguente comando:
- **Get-ChildItem -Path "C:\percorso\della\cartella" -Recurse | Unblock-File
- **Sostituisci "C:\percorso\della\cartella" con il percorso della cartella principale da cui desideri rimuovere il blocco.

Questo comando cercherà tutti i file nella cartella specificata e nelle sue sottocartelle e rimuoverà il blocco da ciascun file trovato.
