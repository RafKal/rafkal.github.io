---
layout: default
title: Rafail Kalenderis
---

# About page

Junior Data Scientist. Hier stehen Exemplare meiner Arbeit.

# 1. Bachelorarbeit
Originalname "Experiments on synthetic Data Time Series Generation using Deep Convolutional GANs"

<!-- # <span style="font-family:Georgia, serif;">"Experiments on synthetic Data Time Series Generation using Deep Convolutional GANs"</span> -->

Die Generierung von Zeitserien ist ein Multidimensionales Thema mit vielen Anwendungsbereichen. Klimawandel, Verkaufszahlen, Biologische Prozesses und mehr können als Zeitserien abstrahiert werden. 

In meiner Abschlussarbeit habe Ich Zeitserien von Sensoren in verschiedenen industriellen Bereichen 
erstellt. Dazu habe Ich WaveGAN (https://arxiv.org/pdf/1802.04208) als "Template" genommen und sämtliche ganzheitliche Achitekturänderungen gemacht.

Die größte änderung war die Addierung von Long-Short-Term-Memory in der üblichen Faltung mit der WaveGAN operierte um upsampling-noise entgegenzuwirken, sowie exklusion von bestimmten schichten und Hyperparameteroptimierung.

Resultat war eine Halbierung der Trainingszeit und eine Weitgehende verbesserung der Zeitserien.


![beispiel](assets/images/bachelor/ecg512.png)

![beispiel](assets/images/bachelor/ecg8192.png)

![beispiel](assets/images/image.png)


# Passager

Bennant von "keyword" + "Passager" handelt es sich hierbei um einen Password Manager, funktionierend mit kxdb Datein und ein Passwordgenerator mit sicheren 128 Hashkeys für erhöte sicherheit. 

Komplett Programmiert in Nativen Java in Android Studio.

![beispiel](assets/images/passager.png)

# Immolink - (Link hier)

Dynamischer und text basierte suche für immobilien.

Irgendwann ist es soweit - Studium ist abgeschlossen und die Wohnungssuche geht los. Dabei bekamm Ich die Idee, eine Semantische Suche selber zu kreieren um den Prozess ggf. zu beschleunugen. Dabei tickt der User keine übliche Filter - er schreibt lediglich was er möchte in Plaintext, und das Programm macht den Rest. 

Technisch gesehen heißt dass, das alle Wünsche durch den User Input extrahiert werden müssen.

 Hier kann Ich klar sagen: Durch ein lokales LLM wie Deepseek oder API basiertes wie ChatGPT wird es viel einfacher. Man gibt den User Input und eine vordefinierte Struktur wie XML und bekommt die Infos die man braucht. Ich wollte es aber mit gängigem und zugänglichen Tools erledigen.

     



