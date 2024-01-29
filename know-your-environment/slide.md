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

# Know your Environment 
Don‘t become a slave of your IDE

---
<!-- 
header: Know your Environment
_class: lead
-->

## Features in VS2022

---
<!-- 
_paginate: hold 
_header: Know your Environment - Features in VS2022 
_footer: Einleitung | **Features** | Extensions | Texteditor
-->
### Dokumente/Tabs 

* Dokumente können in mehreren Reihen angezeigt werden
* Dokumente können gepinnt werden
* Dokumente können farblich gruppiert werden
* Dokumente können in Preview-Tab geöffnet werden

<span style="color:red;">TODO:</span>#addscreenshot

<!--
== mehrreihige Tabs ==
 + Tabs können in mehreren Reihen angezeigt werden
 + Reihen werden automatisch nach Umbruch (wenn Zeile voll) erstellt
-->
<!--
== gepinnte Tabs ==
 + Tabs können angepinned werden
 + Gepinnte Tabs können in einer eigenen Reihe angezeigt werden
 + Pin-Status kann beibehalten werden
-->
<!--
== farblich gruppierte Tabs ==
 + Tabs können farblich gruppiert werden
 + es kann nach Projekt, Extension oder einer RegEx unterschieden werden
 + Farbauswahl erfolgt automatisch, kann aber bei Bedarf angepasst werden
-->
<!--
== Preview Tab ==
  + einmaliges Anklicken öffnet die Preview
  + es ist immer nur ein Dokument in der Preview sichtbar
  + Dokument wir temporär geöffnet und angezeigt
  + Tab ist dabei ganz rechts außen
  + Preview wird zu "richtigem" Tab bei Änderung im Dokument 
    oder Doppelklick 
    oder durch "Keep open" button
-->
<!--
== Wie nutze ich das? ==
  + zur Orientierung und Navigationsunterstützung
  + Mehrzeilige Tabs, um alle Tabs im Blick zu haben, auch wenn es mal mehr sind
  + der aktive Tab ist immer fett gedruckt, damit besser erkennbar
  + ich pinne Dokumente, wenn ich die oft brauche oder oft suchen muss
  + Preview verhindet das unnötige öffnen/schließen, wenn man quasi im Code stöbert
      => z.B. beim Suchergebnisse durchgehen
-->
<!--
== Einstellungen ==
  -> "Show tabs in multiple rows"
  -> "Bold text on selected tabs"
  -> "Colorize document tab by"
  -> "Show pinned tabs in a seperate row"
  -> "Show Pin button on unpinned documents"
  -> "Maintain pin status if document was removed from document welL"
-->
---
<!--
_paginate: hold 
_header: Know your Environment - Features in VS2022 
_footer: Einleitung | **Features** | Extensions | Texteditor
 -->

### Scrollbar

* kann als Navigations und Suchinstrument genutzt werden
* verschiedene Aspekte können in der Scrollleiste angezeigt/geflaggt werden
* es können untershiedliche Breiten eingestellt werden

![center width:90%](./assets/wide_scrollbar_options.jpg)

<!-- 
* können in den Optionen eingeschaltet werden  
* verschiedene Informationen zum aktuellen Dokument können schnell erfasst werden
-->
<!--
== Wie nutze ich das? ==
  + zum erkennen der groben Struktur eines Dokuments
  + zur unterstützung bei der Suche nach Verwendungen, Fehlern innerhalb eines Dokuments
-->
---
<!-- 
_class: lead 
-->
## Extensions

---
<!--
_paginate: hold
_header: Know your Environment - Extensions
_footer: Einleitung | Features | **Extensions** | Texteditor
-->
### Productivity Power Tools 2022

* Satz von verschiedenen Extensions von Microsoft DevLabs
* Match Margin
* Fix Mixed Tabs
* Solution Error Visualizer
* Time Stamp Margin
* [VisualStudio Marketplace](https://marketplace.visualstudio.com/items?itemName=VisualStudioPlatformTeam.ProductivityPowerPack2022)

<!-- 
== interessante Tools ==
* Match Margin 
    => hebt alle Textübereinstimmungen von Token an der Courser-Position im Editor hervor
* Fix Mixed Tabs
    => hilft bei der Verwaltung der Leerzeichen in Dokumenten und unterstützt die einheitliche Verwendung von Tabulatoren und Leerzeichen
* Solution Error Visualizer
    => fügt dem Projektmappen-Explorer Fehler-, Warn- und Meldungs-Kringel hinzu
    => Informationen aus der Fehlerliste, direkt in Strukturansicht des Projektmappen-Explorers angezeigt
    => Popup beim Hovern mit dem Mauszeiger
* Time Stamp Margin
    => Fügt die Zeitstempelinformationen zum Ausgabefenster im Debug-Modus hinzu: (Minuten. Sekunden. Millisekunden)
-->
<!--
== Wie nutze ich das? ==
  + zum schnelleren erkennen von Fehlern
  + zum besseren Finden von Tokens in der Scrollleiste
  + zur einheitlichen Formatierung
-->

---
<!--
_paginate: hold
_header: Know your Environment - Extensions
_footer: Einleitung | Features | **Extensions** | Texteditor
-->
### The Essentials

* Satz von verschiedenen Extensions von Mads Kristensen
* Tweaks
* Output Enhancer
* File Icons
* Insert GUID

<!-- 
== interessante Tools ==
  * Tweaks
      => verschiedene Features und Funktionen aus Funktionsvorschläge und Problemberichtstickets
      => die Liste der Funktionen stammt aus der Visual Studio Developer Community
  * Output Enhancer
      => fügen Sie dem Visual Studio-Ausgabefenster ein Styling hinzu
  * File Icons
      => fügt Symbole für Dateien hinzu, die vom Solution Explorer nicht erkannt werden
  * Insert GUID
      => macht es einfach, eine neue GUID in jeden Editor und jedes Eingabefeld einzufügen
-->
<!--
== Wie nutze ich das? ==
  + Tweaks: Find File in SolutionExplorer
  + Tweaks: Default zoom Level
  + erhöehen der Übersichlichkeit und Usability
-->

---
<!--
_paginate: hold
_header: Know your Environment - Extensions
_footer: Einleitung | Features | **Extensions** | Texteditor
-->
### weitere nützliche Extensions

* Rainbow Braces
* Trailing Whitespace Visualizer
* SonarLint for Visual Studio

<!-- 
== Extensions ==
  * Rainbow Braces
      => Farbliche Kennzeichnung passender Klammerpaare zur einfachen Identifizierung der Paare und ihres Anwendungsbereichs
  * Trailing Whitespace
      => markieren und entfernen Sie alle Leerzeichen am Ende einer Zeile
  * SonarLint
      => SonarLint hilft Bugs, Code Smells und Sicherheitsschwachstellen in-IDE zu erkennen und zu beheben
-->

---
<!-- 
_class: lead 
-->
## Texteditor

---
<!-- 
_paginate: hold
_header: Know your Environment - Texteditor
_footer: Einleitung | Features | Extensions | **Texteditor**
-->
### CodeLens

---
<!-- 
_paginate: hold
_header: Know your Environment - Texteditor
_footer: Einleitung | Features | Extensions | **Texteditor**
-->
### IntelliCode

---
<!-- 
_paginate: hold
_header: Know your Environment - Texteditor
_footer: Einleitung | Features | Extensions | **Texteditor**
-->
### IntelliSense

---
<!-- 
_paginate: hold
_header: Know your Environment - Texteditor
_footer: Einleitung | Features | Extensions | **Texteditor**
-->
### Code Snippets

---
<!-- 
_paginate: hold
_header: Know your Environment - Texteditor
_footer: Einleitung | Features | Extensions | **Texteditor**
-->
### ShortCuts

* Strg K C, Strg K U
* Breakpoints
* Format Document 
* F12 => To Definition

---
<!--
_paginate: hold
_header: Know your Environment - Intellisense/Intellicode
-->
### References 

* Analyzer hints 
* Git hints

---

# Windows
* OUTPUT
* WATCH
* STACKTRACE
* ObjectBrowser
* Intermediate Window

---
# Debugging
* Change vals
* Locals view