# BusinessLab 2026
Interaktive BWL-Lernsoftware für die FOS SAD · created by Theodor-Opa.

## Veröffentlichung
ZIP entpacken. Im Repository businesslab-2026 auf Add file > Upload files klicken. Den Inhalt des entpackten Ordners (nicht den Ordner selbst) inklusive icons-Ordner hochladen. Commit changes wählen. Unter Settings > Pages: main, / (root). Nach erfolgreichem Deployment https://azweck-rgb.github.io/businesslab-2026/ öffnen.

## iPhone
In Safari öffnen, Teilen > Zu Home-Bildschirm hinzufügen, gegebenenfalls Als Web-App öffnen aktivieren. Einmal online laden, bis Offline-Cache vorbereitet erscheint. Danach Flugmodus einschalten und erneut starten, um Offline-Funktion zu testen. Browser können Cache-Daten später löschen.

## Kontrolle
Standardwerte: Herstellkosten 56,40 €, Selbstkosten 62,04 €, Ergebnis 16,96 €/Stück, Gesamt 1.696 €, Rendite 21,5 % (Anzeige gerundet). Fiktives Vollkostenmodell, keine Deckungsbeitragsrechnung.

## Weiterentwicklung
app.js enthält die Berechnungsfunktion calculate. Bei Releases Cache-Version in sw.js erhöhen. Keine externen Bibliotheken oder Tracking-Dienste.

## Version 1.1
Alle Dateien wie bei Version 1.0 ins bestehende Repository hochladen. Das App-Symbol und die URL bleiben gleich. Nach Deployment online neu öffnen, gegebenenfalls zweimal schließen und neu öffnen. Modul 01 bleibt erhalten. Modul 02: Standardwerte Stück-DB 15 €, Auftrags-DB 15.000 €, Vollkostenergebnis −10.000 €, zusätzlicher Ergebnisbeitrag 15.000 €, kurzfristige Preisuntergrenze 40 €. Bei 15.000 € zusätzlichen Fixkosten beträgt der Ergebnisbeitrag null. Bei 500 Stück freier Kapazität muss der Engpass geprüft werden. Offline erneut testen.

## Version 1.2
Vollständiges Update wie zuvor. Modul 03: 79 € Preis, 49 € variable Stückkosten, 30.000 € Monatsfixkosten, 1.200 Stück Absatz, 1.500 Stück Kapazität. Gewinnschwelle 1.000 Stück, Ergebnis 6.000 €, Auslastung 80 %. Preis 49 €: keine Gewinnschwelle. Fixkosten 60.000 €: Schwelle 2.000 Stück, außerhalb der Standardkapazität. Alle Module und Offline-Modus erneut testen.
