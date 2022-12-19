---
title: "Untitled"
author: "Finn Seybold"
date: "2022-12-19"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

# Codebuch

Erhoben wurde das Netzwerk der führenden Köpfe der Reichsbürger, die im Zuge einer Razzia festgenommen wrden   
Quelle: https://taz.de/Razzia-gegen-Reichsbuerger/!5898636/ 

## Edgelist
from = ID des Knoten Mitglied  
to = ID des Knoten Mitgliedschaft  
relation: 1 = Mitglied, 2 = Kolleginnen, 3 = Freunde, 4 = Gründer 

## Nodelist
id = ID aus der Edgelist  
name = Voller Name/Bezeichnung   
type = 1 als Person, 2 als Gruppierung  
sector = z.B. Wirtschaft, Militär, Religion, Politik, Adel, etc.  
