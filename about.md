---
layout: page
title: chi sono
permalink: /about/
---

Mi chiamo Roberto e mi occupo di linguistica, linguistica computazionale e intelligenza artificiale 🌙

```python
import spacy
modello = spacy.load("it_core_news_md")
frase = "la linguistica computazionale è interessante!"
output = modello(frase)
for tok in output:
  print("Parola:",tok.text, "| Ruolo sintattico:", tok.dep_)

# Output:
#   Parola: la | Ruolo sintattico: det
#   Parola: linguistica | Ruolo sintattico: nsubj
#   Parola: computazionale | Ruolo sintattico: amod
#   Parola: è | Ruolo sintattico: cop
#   Parola: interessante | Ruolo sintattico: ROOT
#   Parola: ! | Ruolo sintattico: punct
```

Al momento sto completando gli studi all'Università di Pisa, con una tesi su intelligenze artificiali che usano sia informazione testuale che visuale per predire le emozioni che vengono veicolate dai tweet, e sto per iniziare uno stage nell'ambito dell'NLP.

Fra i miei interessi, [buona e (soprattutto) meno buona musica](https://rateyourmusic.com/~mud__), [i libri, in questo caso esclusivamente buoni](https://www.goodreads.com/user/show/70994255-rob), e cucinare (solo piatti vegetariani, anche in questo caso esclusivamente buoni).

Qui vorrei condividere informazioni su un campo che mi appassiona, e che credo dovrebbe essere più accessibile: la linguistica computazionale. Le risorse al riguardo in italiano infatti non sono molte, così come i corsi, accademici e non. L'obiettivo è quello di essere chiaro a, potenzialmente, chiunque sia interessato a scoprire qualcosina dell'ambito. Ci saranno sicuramente errori, imprecisioni e sviste: chiedo perdono in anticipo e invito chiunque a segnalarle.
