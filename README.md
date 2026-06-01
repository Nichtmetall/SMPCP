# SAP Mass Password Change Parser 🔐

Ein minimalistisches, browserbasiertes Tool, um generierte Passwörter aus SAP-Systemkopien oder -Protokollen schnell zu extrahieren und für den Versand bereitzustellen.

## ✨ Features

* 🚀 **Auto-Parse:** Erkennt SAP-Passwortzeilen automatisch direkt beim Einfügen.
* 📋 **Quick Copy:** Benutzer und Passwörter mit nur einem Klick einzeln kopieren.
* ✉️ **Mail-Integration:** Erstellt per Klick eine fertige E-Mail (`mailto:`) mit personalisiertem Text für den Nutzer.
* 📊 **Sammel-Export:** Exportiert alle Einträge gesammelt als TSV (für Excel/Calc) oder als fertige HTML-Tabelle.
* 🔒 **100% Client-Side:** Keine Daten verlassen deinen Browser. Der Parser läuft komplett lokal.

## 🛠️ Installation & Nutzung

Da das Tool ausschließlich aus einer einzigen HTML-Datei besteht, ist keine Installation notwendig:

1. Lade die Datei `sap_password_parser.html` herunter.
2. Öffne die Datei mit einem Doppelklick in einem beliebigen Browser.
3. Kopiere deinen SAP-Output in das Textfeld – fertig!

## 📝 Unterstütztes Format

Der Parser reagiert standardmäßig auf das typische SAP-Muster:
`Generiertes Kennwort für Benutzer <BENUTZERNAME> : <PASSWORT>`

---
Erstellt mit ❤️ für eine schnellere SAP-Basis-Administration.
