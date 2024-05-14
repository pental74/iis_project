- Create due user control per gestire le giocate del PC e dell'utente


Purtroppo rimane il blocco sui file - **COME RISOLVERE**
--
**Aprire la powershell di windows** (tasto Windows e digitare "powershell")

Inserire il seguente comando:
- **_Get-ChildItem -Path "C:\percorso\della\cartella" -Recurse | Unblock-File_**
- Sostituisci **_"C:\percorso\della\cartella"_** con il percorso della cartella principale da cui desideri rimuovere il blocco

Questo comando cercherà tutti i file nella cartella specificata e nelle sue sottocartelle e rimuoverà il blocco da ciascun file trovato.
