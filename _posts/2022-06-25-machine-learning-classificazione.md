---
layout: post
title: "Machine learning di base: classificare i testi"
date: 2022-06-25
tag: concetti base
---

Nel post precedente, ci siamo detti che uno dei compiti principali della linguistica computazionale è quello di estrarre informazione a partire dai testi. Questi ultimi possono essere visti come contenitori di dati molto disordinati: lo stile e le intenzioni dei parlanti fanno sì che una stessa idea (ad esempio un apprezzamento nei confronti di un prodotto) possa essere trasmessa attraverso modi e registri diversi. All'intelligenza artificiale, dunque, spetta il compito di analizzare questi testi così variegati per ricavarne informazioni utili e standardizzate. In termini un filo più tecnici, cioè nei termini del *machine learning*, ciò si realizza addestrando dei classificatori, cioè addestrando dei modelli di IA affinché essi compiano una classificazione dei dati.

**La classificazione dei testi è un'attività che noi parlanti facciamo quotidianamente**. Immaginate di stare chattando con qualcuno, e che quel qualcuno vi dica "ieri sera sono andato al cinema, ma il film era terribile 😒". Leggendo il testo, istantaneamente e automaticamente ci chiediamo se sia un testo positivo o negativo, e lo facciamo perché così come possiamo pensare a come dare una risposta adeguata. Riflettendo sul nostro processo di interpretazione, in particolare, notiamo che in un primo momento il messaggio tende alla positività ("ieri sera sono andato al cinema"), e che poi viene caricato negativamente da alcuni elementi testuali (l'avversativo "ma", "terribile", l'emoji "😒"). Facendo una sorta di sommatoria dei valori dei vari elementi testuali, stabiliamo che il valore generale è negativo, e la risposta che daremo sarà influenzata da questo (difficilmente risponderemo con "ottimo! 😃"). Questo esempio, per quanto semplice, ci permette di capire in maniera intuitiva come "ragionano" i modelli di machine learning.

Posto in termini più tecnici, la classificazione

$$ prova $$
