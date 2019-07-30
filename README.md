# game_of_life_rails

Scrivere un'applicazione full render + API json in Rails >= 5 che implementi il
Game of Life di John Conway.

L'applicazione deve consentire di consultare l'elenco delle Partite e di
provare una nuova Partita.

Per giocare una Partita deve essere possibile impostare la dimensione del mondo.
Alla creazione di una Partita, deve essere generata casualmente una Generazione 0
con delle Cellule vive e altre morte.

Dalla pagina della Partita devono essere create manualmente (per questioni di
semplicità) nuove Generazioni.

Dal momento in cui una Partita termina, deve essere possibile dalla pagina
della Partita scorrere l'elenco delle Generazioni.

In aggiunta alle pagine HTML, le pagine con l'elenco delle partite e l'elenco
delle generazioni devono essere disponibili anche sotto forma di API json con
jbuilder.

## Database

Utilizzare MySQL.

I modelli di base sono 2:
  - Partita (Game)
  - Generazione (Generation)

Valutare autonomamente la creazione di modelli aggiuntivi di supporto se ritenuti
necessari.

## UI

La UI non è importante, un minimo di attenzione al dettaglio è un plus.

Sono necessarie 3 pagine:
  - elenco delle partite;
  - creazione di una nuova partita;
  - singola partita (con creazione di nuove generazioni o visualizzazione delle
  generazioni in caso in cui la partita sia terminata)
