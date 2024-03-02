---
marp: true
theme: gaia  
size: 16:9
paginate: true
backgroundImage: url('./assets/background.svg')
title: Know your Environment
keywords: programming,visual studio,skills,slides
---
 <style>
  img[alt~='center'] {
    display: block;
    margin-left: auto;
    margin-right: auto;
    border: 1px solid #000 ;
  }
</style>
<!-- 
_class: lead 
-->

# Azure Container Apps

---
## Was sind Container Apps
* serverlose Plattform für containerisierte Apps
* man könnte sagen: Kubernetes as a Service

![center h:350](assets/image.png)

---
## Mögliche Szenarien
* Bereitstellen von API's & Anwendungen
* Hosten Services zur Hintergrundverarbeitung
* ereignisgesteuerte Verarbeitung
* Ausführen von Microservices

---
## Features
* HTTPS/TCP Eingänge in Container
* Ausführung bei Bedarf (Zeitgesteuert/Ereignisse)
* Container aus beliebigen Registries
* Verwaltung von Secrets direkt an der Umgebung
* automatiserbare Verwaltung (z.B. CLI, ARM, BICEP)

---
## Dynamische Skalierung
* Container können auf 0 skaliert werden
* HTTP-Datenverkehr
* Ereignisgesteuerte Verarbeitung
* CPU- oder Arbeitsspeicherauslastung