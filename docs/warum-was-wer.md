---
id: warum-was-wer
title: Warum & Was & Wer
---

## Was

Das hier soll in einer App für den Wuppertaler Zoo enden.
Oder besser in zwei Apps: 

* Eine iPhone App
* Eine WebApp

Beide Apps bekommen ihre Daten über dieselbe API.

## Warum

Ich will zwei neue Sachen lernen: 

* Eine iOS App in Swift schreiben
* Eine WebApp mit React (oder Vue oder Svelte ) zusammenstricken

Ich habe noch nie gut Sachen mit "Hello World" Tutorials gelernt, 
ich brauche ein interessantes Problem, dass ich verstehe.

Daher kam ich auf die Idee mit der Zoo-App:

Jeden Samstag gehe ich mit meiner Tochter in den Wuppertaler Zoo.<br/>
Da kenne ich mich aus, es gibt keine App und ich hätte gerne eine.

Und da gibt es viele interessante Aspekte:

* Navigation zwischen den Gehegen
* Indoor-Navigation in den Häusern
* Zuordnung von aktueller Position zu Tieren

Außerdem scheint das Problem handlebar:

2018 kamen laut [Kulturbericht der Stadt Wuppertal](https://www.wuppertal.de/vv/produkte/200/102370100000358034.php) 571.926 Gäste in den Wuppertaler Zoo.<br/>  
Leider geht aus dem Bericht nicht hervor, wieviel *Unique Visitors* das waren.
Ich war 2018 ungefähr 50mal im Zoo, tauche ich in der Zahl der Stadt einmal oder fünfzigmal auf?

Aber den groben Daumen reicht es.

1. Ich nehme mal eine halbe Millionen Zoobesuche an.
2. Es würde mich sehr wundern, wenn mehr als 10% der BesucherInnen überhaupt eine App benutzen würden.
3. In Deutschland hat iOS einen [Marktanteil](https://de.statista.com/statistik/daten/studie/256790/umfrage/marktanteile-von-android-und-ios-am-smartphone-absatz-in-deutschland/) von ca. 20%.

Daraus ergibt sich:

**50.000** potenzielle App NutzerInnen<br/>
**10.000** davon haben iOS<br/>
**40.000** könnten eine WebApp nutzen<br/>

50.000 / 365 Tage / 8 Stunden Öffnungszeit ergibt unter **20** NutzerInnen die Stunde, die auf der Webapp oder einer API aufschlagen.
 
Selbst wenn ich in der Mittagszeit an einem sonnigen Pfingstsonntag um den Factor 100 daneben liegen sollte, dann wären es **2000** NutzerInnen pro Stunde.
Das müßte mein Hetzner-Server abkönnen.

## Wer

Das hier ist eine reines Spaß und Lern Projekt.

Ich bin in keiner Weise durch den Zoo Wuppertal beauftrage.