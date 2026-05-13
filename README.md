# French inflections

## Verb

See [website](https://joshcena.com/notes/french/verb-conjugation/).

The data is collected from https://github.com/ianmackinnon/inflect. However, it contains a lot of errors. I manually corrected these as I found them. The data in [french-verb-conjugation.csv](./french-verb-conjugation.csv) represents the correct data to the best of my knowledge.

Generally, the infinitive column is unique, with three exceptions:

- départir: Selon l'Académie, départir et se départir se conjuguent comme partir (en se départant ; je me dépars, il se départ, etc.), mais l'usage leur fait généralement suivre la conjugaison de répartir (en se départissant ; je me départis, il se départit, etc.). [source](https://www.larousse.fr/conjugaison/francais/d%C3%A9partir/2847)
- ressortir: irregular conjugation when meaning "to go out again", regular conjugation when meaning "to come under the jurispendence of". [Wiktionary](https://en.wiktionary.org/wiki/ressortir#French)
- faillir: irregular conjugation when meaning "to almost", regular conjugation when meaning "to go bankrupt". [Wiktionary](https://en.wiktionary.org/wiki/faillir#French)

This dataset also contains archaic spellings, such as "œconomiser" instead of "économiser". It even contains a few words with Middle French conjugation: estre, brusler, esloigner, esposer.

I'm not aware of a single authoritative source of French verb conjugations, so there are certain things that may be wrong or debatable. I usually cross-check on Wiktionary, WordReference, and Larousse, but all of them algorithmically generate conjugations, so they may all fail to capture certain irregularities.
