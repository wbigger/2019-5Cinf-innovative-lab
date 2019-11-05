# VERIFICA TPSI: AWS, HTML5, deploy

Benvenuti alla verifica scritta di TPSI. Buon lavoro!

## Esecuzione del compito
Il compito è diviso in tre fasi:
1. avvio di una macchina EC2 su AWS
1. modifica di una pagina web in locale
1. deploy della pagina web sull'istanza EC2

Operazioni preliminari:
- accedete con il vostro account personale a GitHub (**non sbagliate password!**)
- fate il fork di questo progetto, ma **attenzione**: se vi viene chiesto, fate il fork sul vostro account personale e non sull'organizzazione del progetto di classe
- copiate l'URL del **vostro** progetto
- aprite Visual Studio Code
- fate il clone del progetto
- premete sul pulsante "Go Live" nella barra blu in basso
- a questo punto avete la pagina di riferimento aperta sul vostro browser e potete cominciare lo sviluppo

Accesso ad AWS:
- accedete alla [pagina di login](https://www.awseducate.com/signin/SiteLogin) di AWS Educate
- quando create una nuova istanza, **create una nuova chiave** con il nome **cognome-verifica**; questa chiave dovete metterla sotto revisione su github in modo che io possa accedere alla vostra istanza!
- per le operazioni di configurazione potete usare gli appunti a [questo](https://github.com/wbigger/tpsi-5y/) indirizzo


Attenzione: alla fine della verifica, **non** fermate o terminate l'istanza da voi generata perché mi servirà per la correzione!

Testate il vostro progetto il più spesso possibile per controllare che non sia corretto.

**È possibile** consultare w3school o altri siti di esempio.

Al contrario, **non è possibile** comunicare o copiare dai compagni di classe.

Almeno 5 minuti prima della fine verifica, fate il commit e push di tutte le modifiche in locale. Consigliamo comunque di fare commit e push molto spesso durante la verifica (anche ogni 10 minuti), per evitare di perdere punti.

# Calcolo del punteggio
Tutte le seguenti voci valgono **1 punto**.
Voto massimo: 9.
Per avere il massimo del voto bisogna avere il massimo del punteggio.


## Punti generali
- [ ] corretta indentazione di tutti i file
- [ ] codice che compila senza errori nella console del browser

## Parte prima: AWS
- [ ] creare una istanza Amazon Linux 2
- [ ] creare una istanza del tipo xxx
- [ ] aprire le porte xxx
- [ ] configurare l'istanza con nginx
- [ ] pagina di default nginx correttamente visulizzata nel browser

## Parte seconda: sviluppo web in locale
- [ ] menu a sinistra con voci corrette
- [ ] intestazione della pagina corretta
- [ ] creazione di una card con il titolo
- [ ] slidebar/bottoni all'interno della card
- [ ] creazione corretta di tutte e cinque le card
- [ ] stampare sulla console del browser il valore della slidebar o quando il bottone premuto
- [ ] fare due screenshots e caricarli su git


## Parte terza: deploy
- [ ] download del progetto web sull'istanza
- [ ] corretto deploy del sito nell'istanza
- [ ] pagina visualizzabile da browser con dns pubblico


