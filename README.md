All'interno di questa cartella vi sono due progetti ed un docker-compose file:
<ul>
<li> <i>complete</i>: contiene il servizio <i>app</i>; </li>
<li> <i>demo-gateway</i>: contiene il servizio di gateway. </li>
</ul>

Aziona tutto con docker-compose. <br>
Sono accessibili due routes su localhost:8081:
<ul>
<li> <i>/all</i> per visualizzare tutti i user salvati; </li>
<li> <i>/add</i> per inserire un utente. </li>
</ul>

Il Gateway su localhost:8081 reindirizza verso le rispettive destinazioni, /demo/all e /demo/add sull'applicativo <i>app</i> (anch'esso accessibile dall'esterno, volendo, su localhost:8080).
Per /demo/add è richiesto l'inserimento dei dati da inviare in post e di settare un header per "simulare" un controllo dei permessi che avverrà a livello di gateway.
