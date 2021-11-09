# Määrittelydokumentti #

Aineopintojen harjoitustyö: Tietorakenteet ja Algoritmit

Tietojenkäsittelytieteen kandidaatti

----

## Ohjelmointikieli

Python

## Harjoitustyö

Risti-nolla peli vähintään 20x20 pelialustalla. Tarkoitus on kehittää tekoäly, joka pystyy tehokkaasti suunnittelemaan tulevat siirtonsa ja siten pelaamaan ihmistä vastaan.

## Algoritmit ja aikavaatimukset

Algoritmi käyttää minimax-algoritmiä jota on tehostettu alpha-beta-karsinnalla.  
Minimax algoritmi käy läpi pelin tulevia siirtoja, joista se valitsee optimaalisen vaihtoehdon. Kuitenkin pelilaudan kasvaessa siirtovaihtoehtojen määrä kasvaa niin suureksi, että aikavaatimus alkaisi menemään kohtuuttomaksi ellei jopa mahdottomaksi. Sen vuoksi otetaan mukaan alpha-beta karsinta joka karsii ne hakupuun oksat, joista ei voida saada parempaa lopputulosta kuin sillä hetkellä on jo tiedossa.

Parhaassa tapauksessa aikavaatimus on O(b^d/2)  
Pahimmassa tapauksessa O(b^d)

## Projektissa käytettävä kieli

Projektin koodi ja dokumentointi toteutetaan suomeksi.

## Lähteet

[Wikipedia - Alpha-Beta prining](https://en.wikipedia.org/wiki/Alpha%E2%80%93beta_pruning)  
[Wikipedia - Minimax](https://en.wikipedia.org/wiki/Alpha%E2%80%93beta_pruning)
