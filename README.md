# PaperMC-Archetype [![JitPack](https://jitpack.io/v/DoGame5/PaperMC-Archetype.svg)](https://jitpack.io/#DoGame5/PaperMC-Archetype)

Ein Maven Archetype zur schnellen Erstellung von Minecraft Paper Plugins – optimiert für **Paper 1.20.4**.

> Spare dir die immer gleiche Setup-Arbeit und erstelle in Sekunden ein fertiges Plugin-Grundgerüst!

---

## 🚀 Schnellstart

### 📦 Neues Plugin-Projekt generieren:

```bash
mvn archetype:generate \
  -DarchetypeGroupId=com.github.DoGame5 \
  -DarchetypeArtifactId=PaperMC-Archetype \
  -DarchetypeVersion=PaperMC-1.20.4 \
  -DarchetypeRepository=https://jitpack.io \
  -DgroupId=me.deinname \
  -DartifactId=meinplugin \
  -Dversion=1.0-SNAPSHOT \
  -Dpackage=me.deinname.plugin \
  -DinteractiveMode=false
````

> 🔁 Du kannst `groupId`, `artifactId` und `package` an deine Bedürfnisse anpassen.

---

## 📁 Struktur des generierten Projekts

```text
meinplugin/
├── pom.xml
├── src/
│   ├── main/
│   │   ├── java/me/deinname/plugin/Main.java
│   │   └── resources/plugin.yml
└── ...
```

---

## 🧪 Voraussetzungen

* Java 17+ (empfohlen)
* Maven 3.6.3+
* PaperMC Server (ab 1.20.4)

---

## 🧰 Entwickler-Info

Dieser Archetype nutzt:

* `maven-archetype-plugin`
* eine saubere, minimalistische Plugin-Struktur
* modernes Paper Plugin Setup

---

## 🏷 Lizenz

MIT License – nutzbar für Open Source und kommerzielle Projekte.

---

## 🙌 Mitmachen?

Pull Requests sind willkommen!
Wenn du Vorschläge für weitere Platzhalter, APIs oder Verbesserungen hast, schreib gerne ein Issue oder öffne einen PR.

---

> Entwickelt mit ❤️ von [@DoGame5](https://github.com/DoGame5)
