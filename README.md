# html-css-spotifyweb

Eccoci arrivati a Spotify Web, la nostra prima web app!
Il layout di questo esercizio è diverso da quelli che abbiamo riprodotto fino ad ora: il contenuto della pagina non potrà mai uscire dalla viewport, proprio come una app!
In allegato troverete le screenshot per vedere il layout anche nelle versioni responsive, inoltre troverete dei video per quel che riguarda il comportamento hover, responsive e chiusura del browser in altezza.

## Consigli
1. Questo esercizio si svolgerà in più giorni quindi come sempre pensate prima a far funzionare le macroaree, se quelle funzionano allora passate al dettaglio.
2. Potete utilizzare le regole che abbiamo visto fin ad ora. Ok, ma come fate a scegliere la soluzione giusta? A volte vi sembrerà subito evidente, altre volte potreste complicarvi la vita. Se vedete che una strada non vi sta portando nel posto giusto... potete cambiarla!


## TASK COMPLICATI:
PARTE COLONNA SINISTRA CON SCROLL BAR e Footer che copre la  pagina gaurdare screens, il problema si trova penso nei calcoli VH nel main container background.

UTILIZZO DI NOMENCLATURA BEM UTILIZZO DI MONTSERRAT 
UTILIZZO DI ROOT 
## PROBLEMA GRANDISSIMO, ho sistemato un problema attraverso background color.!


## attenzione a 
.recent-item__image > .recent-item__play-icon {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 2rem;
    color: white;
    opacity: 0;
    transition: opacity 0.3s ease;
    font-family: "Font Awesome 6 Free";
    font-size: medium ;
}

trasform stralate per centrare anziche usare flex

.pallina {
    width: 13px;
    height: 13px;
    background-color: #ffffff; /* Colore della pallina */
    border-radius: 50%; 
    opacity: 0;
    transition: opacity 0.3s ease;
    /* display: none; */
}

si potrebbe usare display none ma pensavo fosse piu okay con opacity

## CONTROLLO TASKS

CHECK RESPONSIVE POSITIVO
CHECK HOOVERS POSITIVO
CHECK OVER FLOW POSITIVO con un leggero bug in main
CHECK HOOVER PLAY POSITIVO
CHECK HOOVER PALLINA POSITIVO