# TRIAS
Mit dem Open Service der TRIAS-API greifen Sie auf die Datenbestände der landesweiten Elektronischen Fahrplanauskunft (EFA-BW) zu. Anwendungen können auf diese Weise fertige Fahrtempfehlungen abrufen, ohne sich Gedanken über Verkehrsbeschränkungen, Umsteigezeiten oder das Routing zu machen. Der Name TRIAS steht für __Travelers Realtime Information and Advisory Standard__ und ist eine vom Verband Deutscher Verkehrsunternehmen (VDV) standardisierte Schnittstelle, die im deutschsprachigen Raum vielfach genutzt wird. Die von der NVBW aktuell betriebene Version ist die 1.2.

Wenn Sie einen Abfahrts- oder Ankunftsmonitor bauen wollen, möchten wir Sie außerdem auf den [MobiData BW® Abfahrts- und Ankunftsmonitor](https://www.mobidata-bw.de/blog/abfahrts-ankunfts-monitor) hinweisen.

Detailliertere Informationen zur Schnittstelle und unterstützten Abfragen finden Sie im [Factsheet TRIAS](https://www.mobidata-bw.de/data/MobiData-BW-Factsheet-TRIAS.pdf).

Die API ermöglicht dabei Abfragen zu einzelnen Verbindungen, als auch Abfahrten einzelner Haltepunkte. Es handelt sich hierbei nicht um einen flächendeckenden, gebündelten GTFS-Realtime-Stream. Anzumerken ist, dass im zeitlichen Nahbereich auch Prognose- und Echtzeitinformationen einzelner Fahrten enthalten sind, sofern diese der NVBW vorliegen. Verantwortlich für die Datengrundlage sind hierbei die Verkehrsverbünde, sowie die jeweiligen Verkehrsunternehmen.

Nutzen Sie diese Schnittstelle, um ein neues Informationsangebot zu entwickeln. Die Daten werden in der gleichen Qualität angeboten, in der sie die Verkehrsunternehmen zur Fahrgastinformation einsetzen.

Als Zugang setzt MobiData BW® eine herstellerneutrale Schnittstelle ein, die auch von anderen Betreibern von Auskunftssystemen angeboten wird, genannt TRIAS. Das Format dieser Schnittstelle ist vom Verband Deutscher Verkehrsunternehmen (VDV) in der VDV Schrift Nr. 431-2 dokumentiert. Diese Schnittstelle ersetzt die frühere EFA-API.

Mittels der TRIAS-Schnittstelle können Sie die historischen Sollfahrplandaten für einen Zeitraum der vergangenen sieben Tage abrufen. Echtzeitdaten der einzelnen Fahrten sind hingegen für wenige Stunden in die Vergangenheit nachvollziehbar.

Bei Interesse an einem Zugriff auf die TRIAS-API nehmen Sie gerne Kontakt zu uns auf unter folgender E-Mail-Adresse: mobidata-bw@nvbw.de

Für die Nutzung der APIs gelten folgende Bestimmungen, diese können Sie vorab zur Kenntnis nehmen:

1. Nutzungsbedingungen TRIAS
2. Datenschutzerklärung MobiData BW®
   
Bitte geben Sie dabei folgende Informationen an:

* Vor- und Nachname;
* Name der Institution (bei Privatpersonen reicht der vollständige Name);
* Anschrift;
* E-Mail Adresse, die wir als Kontakt hinterlegen sollen;
* Falls möglich, eine kurze Projekt- und Innovationsbeschreibung, damit mögliche Synergien identifiziert werden können.

Mit Ihrer Kontaktaufnahme akzeptieren Sie die Nutzungsbedingungen. Bei der Übermittlung Ihrer Daten gilt die Datenschutzerklärung von MobiData BW®. Nach einer Prüfung Ihrer Anfrage erhalten Sie einen kundenspezifischen Zugang zu den Datensätzen mit eigenem Endpunkt der TRIAS-API und individualisierter Authentifizierung.

Gerne unterstützt das Team hinter MobiData BW® datenbasierte Projektideen bei ihrem Innovationsprozess, bei der Verbindung möglicher Kooperationspartner, ihrer inhaltlichen Ausgestaltung, und den damit verbundenen grundlegenden technischen Fragestellungen. Eine engmaschige Unterstützung bei der programmiertechnischen Umsetzung von Anwendungen ist nicht angedacht.

## Weiterführende Informationen
* [TRIAS-Issues](https://github.com/mobidata-bw/TRIAS/issues)
* Datensatz [Echtzeit-Fahrplandaten ÖPNV Baden-Württemberg](https://www.mobidata-bw.de/dataset/trias) auf MobiData BW®
* [Datenmodellbeschreibung](https://www.mobidata-bw.de/data/Mentz%20Datenmodellbeschreibung_%20TRIAS%201.2%20Dokumentation%20-%20Trias%201.2%20Kundendokumentation.pdf)
* [VDV-Dokumentation](https://www.vdv.de/ip-kom-oev.aspx)
* [Beispiel-Requests](https://www.mobidata-bw.de/data/Beispielrequests.zip)
