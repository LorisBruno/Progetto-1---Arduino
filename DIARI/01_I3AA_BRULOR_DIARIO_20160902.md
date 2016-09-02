# DIARIO PRIMO PROGETTO

Modulo 306 <br>
Luogo: Trevano, SAMT <br>
Data: 02.09.2016

## Lavori svolti

Dalle 10.05 alle 10.45 i docenti ci hanno fatto un'introduzione al modulo 306 e in seguito, dalle 10.45 alle 11.35 ci hanno spiegato funziomento dei progetti che dovremo svolgere durante l'anno e di cosa tratta il primo progetto. Nel pomeriggio, dalle 13.15 alle 16.30 abbiamo configurato GIT. Per prima cosa abbiamo creato un account su [GitHub](https://github.com) e creato una *Repository*. Nel computer abbiamo dovuto installare [GIT](https://git-scm.com/). In seguito abbiamo installato il client [SourceTree](https://www.sourcetreeapp.com/) e collegato ad esso l'account GitHub. Qui abbiamo riscontrato l'errore del proxy (vedi "problemi e soluzioni"). Una volta risolto questo problema abbiamo guardato come funziona il sistema di caricemento dei file su GitHub tramite SourceTree. Personalmente ho provato a creare un file, committarlo ed infine inviarlo a GitHub.

## Problemi riscontrati e soluzioni adottate


**Problema**: Ho riscontrato un problema con il programma SourceTree, che mi dava un problema di **proxy**.<br>**Soluzione**: Per risolvere questo problema abbiamo dovuto modificare il file *.gitconfig* (che a sua volta rappresentava un problema, vedi di seguito) inserendo i seguenti dati: <br>   [http]<br>proxy = http://nome.cognome:proxypass@proxy:8080 <br> [https] <br> proxy = https://nome.cognome:proxypass@proxy:8080


**Problema**: Una volta intallato SourceTree, nella cartella *C:\users\user\* mancava il file di configurazione *.gitconfig* <br> **Soluzione**: Per risolvere questo problema è bastato andare nella console *GIT Bash* e digitare il seguente comando: <br> git config --global http.proxy http://proxyuser:proxypwd@proxy.server.com:8080 
