
<!--
% This file is part of the Open Source project 'proTirone'
% (c) 2025 Karsten Reincke (https://github.com/protirone)
% It is distributed under the terms of the Creative Commons license
% CC-BY-4.0 (= https://creativecommons.org/licenses/by/4.0/)
-->


<!-- LTeX:Language=de-DE -->
* Download-Repository: [protirone.lessons](https://github.com/protirone/protirone.lessons) | Quellen-Repository *Fachinformatik*: [protico.ltx](https://github.com/protirone/protico.ltx) 

---

## Freie Lehrmaterialien für die Ausbildung zur Fachinformatikerin

<!-- LTeX:Language=en-US -->

> *In Germany, there is a second way to become a computer scientist besides studying computer science: you can get an in-company training as an IT specialist, supplemented by vocational school instruction. Ultimately, you are certified by the Chamber of Industry and Commerce (IHK). This repository offers teaching materials in accordance with the official German framework curriculum. The language of instruction is German. Thus, this repository also uses German as the language of teaching material!* 

<!-- LTeX:Language=de-DE -->

### (1) Manifest

Wir möchten Lehrerinnen und Schülerinnen fertig aufbereitete Unterrichts- und Lerneinheiten für die Ausbildung zur Fachinformatikerin anbieten. Wir wollen den Stoff, den die Abschlussprüfungen I und II erwarten, umfänglich und hochwertig aufbereiten. Und wir wünschen uns, dass jede Nutzerin unsere Ergebnisse im Sinne freier Software und Dokumente gebührenfrei und ohne urheberrechtliche Bedenken verwenden kann.

Deshalb bieten Ihnen die *proTirone*-Repositories **_freie_ Lehr- und Lernmaterialien für die Ausbildung zur Fachinformatikerin**[^1] in Form von Dokumenten und Skripten, 

* die die Vorgaben des Rahmenlehrplans und der Prüfungskataloge erfüllen,
* die sich an die Aufteilung der Lernfelder halten,
* die für sich fertig nutzbare Lehr- und Lernmaterialien bilden,
* die zusammen alle Themen und Aspekte eines Lernfeldes abdecken,
* die *CC-BY-4.0* lizenziert sind.

Wir wissen, dass so ein Ziel nur kooperativ zu erreichen ist. In kleinen Schritten. Deshalb stellen wir unsere Unterrichtseinheiten sukzessive bereit: Wir entwickeln sie zuerst in öffentlichen GitHub-Repositories. Und was reif ist, stellen wir dann als PDF-Dateien in einem Repository für fertige Unterrichtseinheiten zum Download bereit. Beides zusammen -- die GitHub-Methodik und unsere Lizenzierung -- erlaubt es uns, mit Techniken der Open-Source-Softwareentwicklung wirklich freie Unterrichtsmaterialien für die Ausbildung von Fachinformatikerinnen zu entwickeln. Und zwar gemeinsam. Als Community.

Seien Sie als Kontributorin herzlich willkommen! Wir freuen uns auf jeden Pullrequest!!

<p align="center">
  <a href="https://github.com/protirone"><img src="../logo.png" height="80"></a>
</p>

### (2) [Lizenz](../LICENSING.md) 

Sofern im Einzelfall nicht anders vermerkt, stehen alle Dokumente unter der [CC-BY-4.0-Lizenz](https://creativecommons.org/licenses/by/4.0/deed.de). Davon ausgenommen ist das [proTirone-Logo](../logo.png): Es darf nur verwendet werden, um das Projekt [proTirone](https://github.com/protirone) und seine Repositories visuell zu markieren bzw. anzuteasern.

### (3) Struktur

 `proTirone` ist als GitHub-Organisation aufgesetzt und enthält folgende Repositories:

* `protico.lessons` stellt fertige Unterrichtseinheiten zum Download bereit, geordnet nach den Lernfeldern und Curriculum.
* `protico.ltx` enthält LaTeX/Markdown-basierte Quellen für Unterrichtseinheiten samt Build-System.
* `protico.mso` soll einmal Microsoft-Office-Dokumente für Unterrichtseinheiten offerieren
* `protico.mdd` enthält die selbstreferentiellen Quellen für ein Markdown-Demo-System.

### (4) Hintergrund

In Deutschland gibt es neben dem Studium der Informatik die Ausbildung zur Fachinformatikerin.[^1] Ersteres schließt mit dem Bachelor oder Master ab, Letztere mit dem Gesellenbrief. Denn die Ausbildung zur Fachinformatikerin ist Teil des deutschen dualen Ausbildungssystems: Die 'Azubis' - die *Tirones* - werden im Betrieb und in der Berufsschule ausgebildet. Und für die Ausbildung in der Berufsschule braucht es - neben Lehrerinnen und einem Rahmenlehrplan - ein Curriculum und entsprechende Lehrmaterialien.

Wäre es nicht schön, wenn die zukünftigen Informatikerinnen gleich anhand von Open-Source-(Software) basierten Dokumenten ausgebildet würden?

### (5) Warum nutzt Ihr einen lateinischen Projektnamen?

Wann immer wir nach *Fachinformatik* 'gegoogelt' hatten, sind wir auf Treffer zur universitären Informatik gestoßen: Die Bedeutungen von *Fachinformatik* und *Fach Informatik* liegen einfach zu eng beieinander. Auch die Wörter *Lehrling* oder *Lehrlingsausbildung* führen über *Lehre* und *Bildung* in den universitären Kontext.[^2] 

Um nun unser Vorhaben explizit in den Kontext der deutschen Lehrlingsausbildung - das deutsche duale Ausbildungssystem - zu stellen und vom universitären Anspruch abzugrenzen, haben wir uns für das lateinische Wort [tiro = Lehrling](https://de.pons.com/übersetzung-2/latein-deutsch/tiro) entschieden, das - verbunden mit der Präposition *pro* - im Ablativ genutzt wird, also **pro tirone**. (Anfänglich hatten wir noch den Neologismus [computatrum = Rechenmaschine/Computer](https://www.latin-is-simple.com/de/vocabulary/noun/6131/) im Ablativ hinzugefügt, also **pro tirone computatri** = *für den Lehrling der Fachinformatik*. Aber schlichter ist besser.)

[^1]: Wir nutzen das generische Femininum. Dort, wo wir es nicht tun, hätten wir es tun sollen und werden es nachbessern. Denn nach mehreren Jahrhunderten, in denen es andersherum lief, werden wir Männer es gut einige Jahrzehnte aushalten, wenn nun wir mitgemeint sind, und nicht mehr die Frauen. Die werden das zumeist (wohl) nicht (offen) fordern. Weil sie ja ein gerechteres System wollen. Aber wir Männer können es ihnen von uns aus geben, ritterlich. Das wäre dann unser Beitrag zu einer respektvolleren Welt und zur Bewahrung einer gewissen sprachlichen Eleganz. Denn [Sprache ist, was wir draus machen](https://www.amazon.de/Sprache-ist-was-draus-machst/dp/342644612X/).

[^2]: Klar, für solche Fälle gibt es die Spezial(!)suche __"__Fachinformatik__"__. Nur muss man darauf erst einmal kommen. 

