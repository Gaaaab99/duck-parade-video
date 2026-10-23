## Handoff tra sessioni

In qualsiasi progetto, mantieni un file `HANDOFF.md` nella root del repository corrente con lo stato del lavoro. Se non esiste, crealo al primo handoff.

Quando crei o aggiorni `HANDOFF.md`, controlla il `.gitignore` del repository: se `HANDOFF.md` non è già presente, aggiungilo (se `.gitignore` non esiste, crealo). Gli appunti di sessione non devono finire nei commit.

### Quando scrivere l'handoff
- Quando il contesto della sessione si sta riempiendo
- Quando finisci una fase o un task importante
- Quando te lo chiedo ("fai l'handoff" / "handoff")

### Cosa scrivere in HANDOFF.md
Sovrascrivi il file ogni volta (non accodare): deve descrivere solo lo stato attuale.
- **Obiettivo**: cosa stiamo cercando di ottenere e task in corso
- **Fatto**: cosa è stato completato in questa sessione
- **Decisioni**: scelte prese e perché
- **File**: file toccati e file rilevanti da leggere per ripartire
- **Aperto**: bug noti, problemi irrisolti, cose da verificare
- **Prossimi passi**: azioni concrete, in ordine di priorità
- **Comandi utili**: come buildare/testare/avviare, se rilevante

Sii conciso ma completo: deve bastare a una sessione nuova, senza altro contesto, per riprendere il lavoro. Non duplicare ciò che è già in CLAUDE.md.

Dopo averlo scritto, dimmi: "Handoff fatto: fai /clear e poi scrivi continue".

### Quando inizia una sessione nuova
Se scrivo "continue" o "continua", leggi `HANDOFF.md` del progetto corrente e riprendi dai prossimi passi senza chiedermi di rispiegare. Se il file non esiste, dimmelo.
