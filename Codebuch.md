---
title: "Codebuch"
author: "Laura Wallenfels"
date: "19 5 2022"
output: html_document
---

## Ursprung und Datenerhebung

Die Daten wurden aus der aktuellen Kaderliste des VFB Stuttgart Kaders entnommen: <https://www.transfermarkt.de/vfb-stuttgart/startseite/verein/79>

## Edgelist

from,to,weight,season

from = von welchem Verein kommt der Spieler \

to = ID des Spielers (Rückennummer)

weight = Transfersumme in 100.000 Euro Schritten, gerundet falls abweichend.

season = transferfenster. nur erste Jahreszahl des Fensters als JJJJ verwenden.

## Nodelist

id, name,country,type

id = Rückennumer oder Vereinsname

name = Spieler oder Vereinsname

country = Land

type

1 = Spieler,

2 = Verein
