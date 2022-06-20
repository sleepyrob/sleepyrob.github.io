---
layout: page
title: Chi sono
permalink: /about/
---

## Chi sono

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

Qui vorrei condividere quel che so su un ambito che credo dovrebbe essere accessibile a tuttə e non appannaggio di pochə. Chiedo perdono per gli errori, le sviste, i passaggi poco precisi che, sicuramente e inevitabilmente, ci saranno.
