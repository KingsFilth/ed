---
layout: narrative
title: WordPress, Squarespace oder doch alles selber machen
author: Laurenz Junker
publication-date: 2022-06-23
custom_excerpt: "Wer sich nicht an eine Plattform binden möchte, dem bleibt nur eins: selbst Hand anlegen."
---

Wo startet man, wenn man eine Webseite bauen möchte? Im Internet gibt es Anbieter von Hostern wie Sand am Meer. Hinter ihnen steht ein Contentmanagement System (CMS), also eine Umgebung, in der man die Seite editieren, Artikel hinzufügen und as Design ändern kann. Alles im Browser und alles mit verschiedensten Modulen. Am bekanntesten dürfte wohl WordPress sein, mittlerweile gesellt sich auch, nicht zuletzt durch die unglaublich vielen Werbepartnerschaften mit Youtubern, Squarespace dazu. Die Vorteile liegen auf der Hand, Wissen über HTML-Code oder CSS sind nicht mehr nötig, alles kann im CMS selbst konfiguriert werden. Die Nachteile sind jedoch die eigeschränkte Konfigurierbarkeit, die Module sind zwar editierbar, schränken aber auch vieles sein. Dazu kommt die Abhängigkeit an eine Plattform, die Daten zur Nutzung sammelt oder Geld kostet.
Die Alternative: Die Webseite (weitestgehend) selber bauen, so wie ich es hier gemacht habe. Der grundliegende Code ist Jekyll, welcher aus meinem geschriebenen Code statische Webseiten generiert. Ich gebe also die Befehle und Jekyll baut daraus meine Seite. Das bedeutet, dass ich HTML und CSS lernen muss, damit ich überhaupt valide Befehle geben kann. 
<br>
Was mir persönlich an dieser Methode gefällt ist, dass ich zu jeder Zeit nachvollziehen kann, was auf meiner Webseite passiert. 90% des Internets läuft mittlerweile über Javascript, dadurch sieht zwar alles ein bisschen schicker aus, macht das Ganze aber auch undurchsichtiger und vor allem anfälliger für Angriffe. Vor allem wird damit (sowie mit Cookies) Aktivität auf Websiten verfolgt. Genau diese Tracker werden bei CMS-Systemen von Haus aus mitgeliefert, immerhin verdienen die Anbieter so ihr Geld. 
Diese Webseite nutzt zum Beispiel nur einmal Javascript: für das öffnen und schliessen der Seitenleist mit dem Button links oben. Cookies werden keine gesetzt, hier geht es einfach nur um den Inhalt. 