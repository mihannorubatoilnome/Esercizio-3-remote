# Git - Working with Remotes
- I repository remoti sono versioni del tuo progetto che sono ospitate su Internet
- La collaborazione con altri programmatori implica la gestione di questi repository e il push e il pull di dati

Fondamentalmente è saper **sincronizzare il nostro locale con repository remoto.**

*comandi principali:*

`git remote -v` --> visualizza i server remoti collegati al nostro repository

### Aggiungere o rimuovere un repository remoto

`git remote add <nome> <url>`

### Caricare il lavoro sul repository remoto

`git push <remote> <ramo-locale>`

### Aggiornare la copia locale del repository, allineandola con la versione remota

`git pull <remote> <ramo-locale>`
