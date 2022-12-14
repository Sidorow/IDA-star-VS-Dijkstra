# Määrittely

Ohjelman tavoitteena on vertailla IDA* -ja Dijkstran algoritmeja suunnatussa painotetussa verkossa. Verkko voi olla labyrintti, jossa koordinaatit toimivat verkon solmuina. Ohjelma toteutetaan Python -kielellä. Vertaisarviointia varten myös javakoodin lukeminen onnistuu.

## Algoritmit ja tietorakenteet

Työssä toteutetaan IDA* ja Dijkstran algoritmi. Tietorakenteina toimivat Pythonin taulukko, jota käytetään pinon tavoin. Sama onnistuisi myös Collections -kirjaston deque:lla. Dijkstran prioriteettijono toteutetaan kurssin ohjeiden mukaisesti itse tehokkaasti keolla.

## Ongelma ja syötteet

Ongelmana toimii kartta/labyrintti/verkko, josta halutaan päästä lyhimmällä polulla pisteestä X pisteeseen Y. Olen ennen tutustunut A* -algoritmiin, joten tälle sukua oleva IDA* kiinnostaa. Syötteenä ohjelma saa verkon, josta se pyrkii löytämään lyhimmän/halvimman polun pisteestä pisteeseen. Ohjelma toteuttaa samalle verkolle sekä IDA*- että Dijkstran algoritmin, joista sitten otetaan ulos mm aika ja käytyjen solmujen määrä ja myös jonkinlainen visuaalinen representaatio läpikäydystä polusta.

## Aika- ja tilavaativuudet

### IDA*

- Aikavaativuus
	- O(n^m)

- Tilavaativuus
	- O(n)       

### Dijkstra

- Aikavaativuus
	- O(n + m log n)

- Tilavaativuus
	- O(n2)

## Kurssiin liittyvät asiat

- Opinto-ohjelma tietojenkäsittelytieteen kandidaatti (TKT)

- Projektin kieli Suomi

## Lähteet

https://en.wikipedia.org/wiki/Iterative_deepening_A*#Properties

https://en.wikipedia.org/wiki/Iterative_deepening_depth-first_search#Time_complexity

Tietorakenteet ja Algoritmit -kurssikirja
