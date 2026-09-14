---
title: "K-Means Algorithmus"
tags: [machine-learning, algorithm]
aliases:
  - "k-means"
  - "K-Means"
  - "KMeans"
---

# K-Means Algorithmus

Ein weit verbreiteter, partitionsbasierter Algorithmus des [[Unsupervised Learning|unüberwachten Lernens]], der einen Datensatz iterativ in eine vorab festgelegte Anzahl ($K$) von [[Clusteranalyse (Clustering)|Clustern]] unterteilt. Er platziert $K$ Zentren im Datenraum und verschiebt sie Schritt für Schritt so lange, bis sie exakt die Mittelpunkte der zugehörigen Datenpunkte bilden.

1. **Zufällige Initialisierung**: Zu Beginn werden $K$ Clusterzentren zufällig im Datenraum positioniert.
2. **Zuweisung**: Jeder einzelne Datenpunkt wird dem mathematisch nächstgelegenen Clusterzentrum zugeordnet.
3. **Neuberechnung des Zentrums**: Die Position jedes Zentrums wird als rechnerischer Mittelwert (Mean) aller ihm im Schritt 2 zugewiesenen Datenpunkte neu berechnet.
4. **Iterative Wiederholung & Konvergenz**: Die Schritte 2 und 3 werden in mehreren Runden wiederholt. Mit jedem Durchlauf passen die Punkte ihre Zugehörigkeit an und die Zentren wandern in Richtung der wahren Dichtezentren. Das Verfahren stoppt, sobald sich die Positionen der Zentren nicht mehr verändern.

**Verwandte Begriffe:** [[Clusteranalyse (Clustering)]], [[Unsupervised Learning]], [[Algorithmus]], [[k-naechste-nachbarn]], [[Maschinelles Lernen]]
