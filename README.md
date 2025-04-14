# Python-Code-zur-Statistik_-BNE-Wortschatz-
Python-Code zur Berechnung der relativen Häufigkeiten und zum statistischen Vergleich mit dem Ziel der Ermittlung des BNE-Wortschatzes

# BNE-Wortschatz-Statistik
Relative Häufigkeiten und induktiv-statistischer Vergleich zu BNE-Wortschatz.

# Wortarten
Es wurden die Wortarten (1) Nomen, (2) Adjektive und (3) Verben untersucht.

# Korpora als Vergleichsgrundlage
Es wurden 3 Korpora miteinander verglichen: 1. Der eigene BNE-Korpus (Korpus 1) 2. Der childLex-Korpus (Korpus 2) 3. Der Leipziger-Nachrichten-Korpus (Korpus 3).

# Aufbau der ausgegebenen Daten:
1. Zunächst wurden die relativen Häufigkeiten berechnet (d.h. Wortfrequenz im jeweiligen Korpus durch Gesamtlemmata- bzw. Type-Anzahl des jeweiligen Korpus).
2. Die Lemmata/Types mit einer höheren relativen Häufigkeit im 1. Korpus ggü. 2. Korpus und 3. Korpus wurden berücksichtigt für nachfolgende vergleichende Statistik.
3. Die statistische Signifikanz der Unterschiede der relativen Häufigkeiten wurde mit Chi-Quadrat-Berechnung unter Berücksichtigung einer Bonferroni-Korrektur berechnet (aufgrund wiederholender Tests; ingesamt 300 Tests).
