# careerspanorama-posizioni

Dati delle posizioni aperte per studenti, letti ogni notte alla fonte (pagine careers e sistemi di reclutamento delle societa'). File JSON statici serviti da GitHub Pages,
gli stessi che il sito mostra a tutti: link all'annuncio originale e societa', e se facili titolo, citta, paese, data, livello e settore. Non copiamo i testi degli annunci.

- `indice.json`: compatto, per la pagina /posizioni/ (campi dichiarati in `campi`).
- `societa/<slug>.json`: stato della societa' e i suoi annunci. `settori/<slug>.json`: gli annunci assegnati a un settore.
- `salute.json`: esito della lettura notturna per fonte.

Una societa' che non vuole comparire puo' chiederlo: la togliamo dall'elenco di esclusione.
