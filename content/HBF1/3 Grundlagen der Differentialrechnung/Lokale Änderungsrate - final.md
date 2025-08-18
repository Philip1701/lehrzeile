---
title: "Lokale Änderungsrate - final"
description: ""
summary: ""
draft: false
weight: 401
toc: true
math: true # für die Nutzung von KaTeX
count: 0 # für die Nummerierung der Aufgaben
---

## Definition

Gegeben ist die Funktion $f$.
Die lokale Änderungsrate von $f$ an der Stelle $x_0$ ist die Steigung der Tangente an dem Graphen von $f$ im Punkt $P\left(x_0|f(x)\right)$.
Die lokale Änderungsrate heißt auch **Ableitung der Funktion an der Stelle $x_0$**.
Geschrieben $f'(x)$ (gesprochen: "f Strich von x null").

{{< box-notice >}}
Die lokale/momentane Änderungsrate einer Funktion ist die **Steigung der Tangente** am Graphen in einem bestimmten Punkt. Mit der momentanen Änderungsrate, die man auch **Ableitung** nennt, kann man die Steigung in jedem beliebigen Punkt einer Kurve bestimmen.
{{< /box-notice >}}

## Bestimmen der mittleren Änderungsrate

{{< youtube sXxK-JATrc0 >}}

{{< job title="Üben und Vertiefen" numbered="true" style="" name="" >}}
Gegeben sei die Funktion $f_1$ mit $f_1(x)=\frac12 x^2 - 3x + 1$.

1. Bestimme mithilfe des Differenzenquotienten die mittlere Steigung im Intervall $[-2;1]$.
2. Bestimme nach demselben Prinzip die mittlere Steigung im gleichen Intervall, dieses Mal jedoch in Einerschritten ($[-2;-1]$, $[-1;0]$ und $[0;1]$).
3. Treffe eine Aussage über einen möglichen Zusammenhang zwischen den mittleren Steigungen aus den Aufgabenteilen 1 und 2.
{{< /job >}}

## Bestimmen der lokalen Änderungsrate

Mit Hilfe des Differenzenquotienten lässt sich auch - allerdings nur näherungsweise (!) - die lokale Änderungsrate an einer bestimmten Stelle des Funktionsgraphen bestimmen. Hierzu muss notwendigerweise das Intervall um die entsprechende Stelle herum sehr klein (!) gewählt werden.

{{< job title="Üben und Vertiefen" numbered="true" style="" name="" >}}
Gegeben sei die Funktion $f_1$ mit $f_1(x)=\frac12 x^2 - 3x + 1$.

1. Bestimme mithilfe des Differenzenquotienten die Steigung im Punkt $P_1 \left(3|f(3)\right)$, indem du schrittweise die Intervallgrenzen verschiebst ($\pm 0,5 \rightarrow \pm 0,1 \rightarrow \pm 0,01$).
{{< /job >}}

### Methode #1: Näherungstabelle bzw. Differenzenquotient

<!-- ![image](Bestimmen_der_lokalen_Änderungsrate.jpeg) -->

folgt...

### Methode #2: Grenzwertbetrachtung

folgt...

### Methode #3: Anwenden der Ableitungsregeln

folgt...

## Interpretation der lokalen Änderungsrate im Beispielkontext

| Bsp.e für Funktionen | mittlere Änderungsrate | lokale Änderungsrate |
| --- | --- | --- |
| Zeit → zurückgelegter Weg | Durchschnittsgeschwindigkeit | Momentangeschwindigkeit  |
| Entfernung → Höhe | Durchschnittshöhe | Momentane Steigung |
