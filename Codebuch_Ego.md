---
title: "Codebuch_Ego"
author: "Lara Gebhart, Yasmin Köseli"
date: '2022-04-23'
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## Codebuch

-   Edges.csv (Edgelist)

-   Nodes.csv (Nodelist)

-   Codebuch.md (Codierung der Datensätze)

#### 
Edge-Atribute

id

codiert nach Anfangsbuchstaben

Jede id steht für eine Person

from

initiierter Knoten (Lara) nennt Alteri, mit denen er wichtige Angelegenheiten bespricht

to

erhaltender Knoten ist präferierender Gesprächspartner

weight

1 = schwache Beziehung

2 = starke Beziehung

3 = sehr starke Bezeihung

relation

1 = Bekanntschaft

2 = Freundschaft

3 = Partnerschaft

#### Node-Attribute

id

Identische ID wie aus der edgelist zur Identifikation der Knoten. Knoten sind personalisiert nach Namen.

name

personalisierte ID

age

Alter in natürlichen Zahlen

education

Bildungsabschluss, als string/characters codiert

religion:

Religionszugehörigkeit, als string/characters codiert
