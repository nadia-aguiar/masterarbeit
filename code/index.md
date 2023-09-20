---
layout: page
title: Code
#excerpt: "A List of Projects"
comments: false
---
Während meines Praktikums hatten mein Betreuer und ich die Idee, einen Code zu schreiben, mit dem Daten aus wissenschaftlichen Zeitschriften, die auf Open-Journal-Plattformen gehostet sind, extrahiert werden können. In Brasilien und Portugal verlagern viele Universitäten und Forschungszentren ihre wissenschaftliche Arbeit auf diese Plattformen. Viele Forscher*innen nutzen die Veröffentlichungen auf diesen Plattformen für ihre Forschungsarbeit. Deshalb dachten wir, dass es eine gute Idee wäre, den „Scraping“ auf diese Daten zu erleichtern, indem wir einen Code schreiben und ihn der Öffentlichkeit zur Verfügung stellen. 

Ich habe also einen Code entwickelt, der die Daten extrahiert und diese Informationen in strukturierter Form an den Forscher*innen weitergibt. Der Code bietet zwei Möglichkeiten, um auf die wissenschaftlichen Artikel zuzugreifen: alle im PDF-Format veröffentlichten Dateien oder die in HTML zur Verfügung gestellten Informationen - leider bietet keine der getesteten Zeitschriften die Artikel in TEI-Datein an. Der Code wurde in Python geschrieben und verwendet die Selenium Web Scraping Bibliothek. Das Repository mit dem geschriebenen Code finden Sie <a href="https://github.com/nadia-aguiar/praktikum_dh_2022" target="_blanck">hier</a>
. 
 
Scließlich wurde der Code mit der Zeitschrift Aceno als Modell geschrieben, aber auch in vier verschiedenen Zeitschriften getestet: Revista Ilha der Universidade Federal de Santa Catarina, Afro-A’sia der Universidade Federal da Bahia, Revista de Estudos e Pesquisas sobre as Américas der Universidade de Brasília (UnB) und CROLAR - Critical Reviews on Latin American Research. Der Code funktionierte in allen Zeitschriften. Diese Zeitschriften wurden bewusst ausgewählt. Sie konzentrieren sich auf lateinamerikanische, indigene, Schwarze und LGBTQI*-Themen.