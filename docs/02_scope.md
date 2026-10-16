# Scope des ISMS

## 1. Zweck ##
Dieses Dokument definiert den Geltunsgbereich (Scope) der Informationssicherheits-Risikoanalyse für die fiktive Noventis Group GmbH. Es legt fest, welche Organisationseinheiten, Geschäftsprozesse, Informationswerte, IT-Systeme und Standorte im Rahmen der Analyse betrachtet werden. 

Ziel ist es, die Grenzen der Risikoanalyse nachvollziehbar festzulegen und sicherzustellen, dass relevanten Risiken für die Vertraulichkeit, Integrität und Verfügbarkeit von Informationen identifiziert, bewertet und behandelt werden können. 

Die Risikoanalyse dient als Grundlage für den schrittweisen Aufbaue eines ISMS nach ISO 27001:2022. 

**Achtung** : Dieses Projekt dient ausschließilch zum Lernen und zu Demonstrationszwecken. 

---

## 2. Organisation und Geltungsbereich ##
Die Risikoanalyse betrachtet die zentralen Geschäftsprozesse und Informationsverarbeitenden Tätigkeiten der Noventis Group GmbH am Hauptsitz in Nürnberg sowie die für die betrachteten Prozesse relevanten weiteren europäischen Standorten. 

**Folgende Geschäftsbereiche sind eingeschlosse:**
- **Noventis Engineering:** Entwicklung industrieller Software, Embedded Systems und Automatisierungslösungen sowie Verwaltung von Quellcode und Entwicklungsumgebungen.
- **Noventis Digital Servies:** Betrieb von Cloud-Anwendungen, Datenplattformen und gehosteten Kundenanwendungen  sowie erbringung von Managed IT-Services.
- **Noventis Advisory:** Erbringung von Beratungsleistungen in den Bereichen IT-Strategie, Compliance, Risikomanagement und Informationssicherheit.
- **Noventis Corportate Solutions:** Unterstützt interner Geschäftsprozesse, insebesondere Finanzen, Personalwesen, Einkauf sowie Vertrags- und Rechtsmanagement

Zusätzlich werden die zentralen Unterstützungs- und Führungsfunktionen berücksichtigt, soweit sie Einfluss auf die Informationssicherheit der eingeschlossenen Prozesse haben. Dazu gehören insbesondere Geschäftsführung, IT-Betrieb, Cloud und Plattformmanagament, Informationssicherheitsmanagement, Datenschutz, Personal und Lieferantenmanagement. 

---

## 3. Räumlicher Gelatungsbereich ## 
Die Risikoanalyse umfasst den Hauptsitz in Nürnberg sowie weitere Standorte, soweit dort Informationen verarbeitet, IT-Dienste genutzt oder Geschäftsprozesse ausgeführt werden, die zum definieren Untersuchungsbereich gehören. 

Besonders berücksichtigt werden die beiden Rechenzentren in Nürnberg und Frankfurt sowie die für die Geschäftsprozesse relevanten Cloud. und Netzwerkumgebungen. 

Die 12 weiteren europäischen standorte werden im Rahmen der Risikoanalyse hinsichtlich ihrer relevanten Informationswerte, IT-Anbindungen und organisatorische Abhängigkeiten betrachtet. Eine detaillierte Einzelanalyse jedes Standorts erfolgt nur, soweit dies für die Bewertung der betrachteten Risiken erforderlich ist. 

--- 

## 4. Technischer Geltungsbereich ## 
Der technische Geltungsbereich umfasst alle IT-Systeme, Plattformen und Infrastrukturen, die für die eingeschlossenen Geschäftsprozesse eingesetzt werden oder deren Informationssicherheit wesentlich beeinflussen. 

Dazu gehören insbesondere: 

- **Identitäts- und Zugriffsmanagement:** Active Directory und Microsoft Entra ID.
- **Kommunikation und Zusammenarbeit:** Microsoft 365 mit Exchange, Teamd und Sharepoint
- **Geschäftsanwendungen:** ERP-System und CRM-System.
- **Softwareentwicklug:** GitLab, GitHub Enterprise sowie zugehörige CI/CD-Pipelines.
- **Cloud Infrastruktur:** AWS, Azure und die private Cloud.
- **Rechenzentren:** Server-, Speicher und Netzwerkkomponenten der Rechenzentren in Nürnberg und Frankfurt
- **Datensicherung und Wiederherstellung:** Backup-Systeme sowie zugehörige Wiederanlauf- und Wiederherstellungsverfahren. 
- **Sicherheitsüberwachung:** SIEM, Firewall- und IDS/IPS-Systeme sowie die damit verbundenen Überwachungsprozesse
- **IT-Service-Management:** Ticketing-Systeme und unterstützende Betriebsprozesse. 
- **Netzwerk und Endgeräte:** Standortvernetzung, VPNm VLAN-Segmentierung, WLAN sowie zentral verwaltete mobile Geräte

Schnittstellen zu industriellen Steuerungs- und Produktionsumgebungen (OT) werden berücksichtigt, sofern sie durch Entwicklungsleistungen, Fernzugriffe, Datenübertragungen oder andere Abhängigkeiten mit den eingeschlossenen IT-Systemen und Geschäftsprozessen verbunden sind. 

--- 

## 5. Informationswerte und Datenarten ## 
Die Risikoanalyse berücksichtigt Informationen und sonstige schützenswerte Werte, die innerhalb des definierten Geltungsbereichs verarbietet, gespeichert, übertragen oder verwaltet werden. 

Hierzu zählen insbesondere: 

- personenbezogene Daten von Beschäftigten, Kunden und Bewerbern.
- vertrauliche Geschäfts-, Finanz- und Vertragsinformationen.
- Kundenprojektinformationen, Systemkonfigurationen und Zugangsdatten.
- Quellcode, technische Entwürfe und sonstige geistiges Eigentum.
- Betriebs-, Protokollierungs- und Monitoringdaten.
- öffentilch bestimmte Informationen, bspw. Website- und Markentinginhalte.

Die Bewerung des Schutzbedarfs orientiert sich an den möglichen Auswirkungen einer Verletzung der Vertraulickeit, Integrität oder Verfügbarkeit. Die konkrete Risikobewertung erfolgt anhand der in der Methodik und den Bewerungsskalen festgelegten Kriterien. 

--- 

## 6. Prozessbezogener Geltungsbereich ##
Im Rahmen der Risikoanalyse werden insbesondere folgende Prozesse betrachtet: 

- Entwicklung, Prüfung und Bereitstellung von Software.
- Betrieb und Administration von IT- und Cloud-Diensten.
- Verarbeitung und Bereitstellung von Kundeninformationen.
- Identitäts- und Berechtigungsverwaltung.
- Datensicherung, Wiederherstellung und Notfallmanagement.
- Sicherheitsüberwachung und Behandlung von Sicherheitsvorfällen.
- Personalverwaltung und Verarbeitung personenbezogener Daten.
- Finanz- und Zahlungsprozesse.
- Einkauf, Lieferantenmanagement und Steuerung externer Dienstleister.
- Verwaltung vertraulicher Beratungs- und Vertragsunterlagen.

Die Prozesse werden hinsichtlich ihrer Informationswerte, Abhängigkeiten, möglichen Bedrohungen und Auswirkungen auf die Geschäftstätigkeit untersucht. 
