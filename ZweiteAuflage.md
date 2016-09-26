---
layout: default
title: "2. Auflage"
description: Neues in der zweiten Auflage
---

Die Neuauflage wurde in Bezug auf Werkzeuge wie Docker, Jenkins, Graphite und den ELK-Stack aktualisiert. An neuen Themen sind Docker Compose, Docker Machine, Immutable Server, Microservices und die Einführung von Continuous Delivery ohne DevOps hinzugekommen. Im Einzelnen:

* Der neue Abschnitt 3.6 beschreibt das Konzept "Immutable Server",
  bei dem Server niemals mit Updates versehen werden, sondern
  unveränderlich sind. Das macht Installationen einfacher
  reproduzierbar.
  
* Docker ist ein sehr interessantes Werkzeug für das Deployment von
Software. Docker Machine vereinfacht die Installation von Docker-
Servern. Der neue Abschnitt 3.5.5 beschreibt Docker Machine. Mit
Docker Compose können mehrere Docker Container zusammen installiert
werden – das beschreibt der neue Abschnitt 3.5.7.

* Continuous Delivery und DevOps haben viele Synergien – aber
Continuous Delivery ist auch ohne DevOps möglich. Das beschreibt der
neue Abschnitt 11.4.

* Der neue Abschnitt 12.6 erläutert Microservices-Architekturen und die
Beziehung zu Continuous Delivery.

* Der ELK-Stack zum Speichern und zur Analyse von Logs in
Abschnitt 9.3 nutzt die aktuelle Version von Elasticsearch (2.1),
Logstash (2.1) und Kibana (4.3). Dabei hat sich die Installation, aber
auch die Oberfläche geändert – deswegen waren auch Ände- rungen im
Abschnitt "Experimente und selber ausprobieren" notwendig. Die
Installation ist nun nicht nur mit Vagrant, sondern auch Docker
Machine möglich.

* Das Monitoring mit Graphite in Abschnitt 9.8 ist
jetzt wesentlich besser modularisiert: Ein Docker-Container nimmt die
Metriken entgegen, ein anderer bietet die Webschnittstelle zur Analyse
der Daten.

Auch hier kann das Beispiel nun mit Docker Machine statt
Vagrant genutzt werden.  In der 2. Auflage wurden die Beispiele auf
aktuelle Versionen der Werkzeuge umgestellt.

Konkret:

* Die Beispiel-VMs benutzen jetzt Ubuntu15.04.

* Die Beispielanwendung verwendet SpringBoot1.3.0.

* Das Chef-Beispiel in Abschnitt 3.3 wurde aktualisiert auf Chef 12, Java 1.8 und
Tomcat 7

* Docker aus Abschnitt 3.5 basiert jetzt auf Docker1.10.

* Selenium für GUI-Tests in Abschnitt 5.4 wird in der Version 2.48.2 verwendet.
