Aziona tutto con docker-compose. <br>
Sono accessibili due routes su localhost:8081:
<ul>
<li> <i>/all</i> per visualizzare tutti i user salvati</li>
<li> <i>/add</i> per inserire un utente </li>
</ul>

Il Gateway su localhost:8081 reindirizza verso le rispettive destinazioni, /demo/all e /demo/all sull'applicativo <i>app</i> (anch'esso accessibile dall'esterno, volendo, su localhost:8080).
