# migRaven.Max-Audit-Template-Prompts
migRaven.Max - Best Practice Prompt Katalog

Übersicht

Dieser Katalog enthält 160 vordefinierte Prompts für das Security Audit Tool migRaven.Max. Die Prompts sind speziell auf die Neo4j Graph-Datenbank-Struktur von migRaven.Max optimiert und ermöglichen umfassende Analysen der IT-Infrastruktur.

Datengrundlage

Die Prompts basieren auf einer umfassenden Analyse der migRaven.Max Neo4j-Datenbank mit folgenden Charakteristiken:

•
66 Node-Typen (User, Computer, Group, EntraUser, TeamsTeam, SharePointSite, etc.)

•
77 Relationship-Typen (MEMBER_OF, HAS_PERMISSION, SYNCED_FROM, etc.)

•
11.745 Knoten in der Beispieldatenbank

•
95.034 Beziehungen zwischen den Objekten

Kategorien

Die 160 Prompts sind gleichmäßig auf 8 Kategorien verteilt (je 20 Prompts):

1. IT Security (20 Prompts)

Fokus auf Sicherheitsbewertung und Schwachstellenanalyse der IT-Infrastruktur.

Beispiel-Themen:

•
Privilegierte Konten ohne MFA

•
Kerberos Delegation Risiken

•
LAPS-Implementierung

•
Service-Account-Sicherheit

•
GPO-Berechtigungen

•
Fileserver-Berechtigungen

2. Verwaltbarkeit (20 Prompts)

Bewertung von Strukturen, Namenskonventionen und Verwaltungskomplexität.

Beispiel-Themen:

•
Namenskonventionen (User, Computer, Gruppen, OUs)

•
OU-Strukturtiefe

•
Leere Organisationseinheiten

•
Gruppenverschachtelungen

•
GPO-Verwaltung

•
Unresolved Principals

3. Onboarding (20 Prompts)

Dokumentation für neue IT-Mitarbeiter basierend auf der aktuellen Infrastruktur.

Beispiel-Themen:

•
Domain-Struktur Übersicht

•
OU-Hierarchie Visualisierung

•
GPO-Landkarte

•
Privilegierte Gruppen

•
Service-Account Inventar

•
Berechtigungskonzept

•
Entra ID Integration

4. Verzeichnisstrukturen (20 Prompts)

Analyse von Fileserver-Strukturen, Dateiablage und Speicheroptimierung.

Beispiel-Themen:

•
Obsolete Verzeichnisse

•
Zu tiefe Verzeichnisstrukturen

•
Dateitypverteilung

•
Berechtigungskomplexität

•
Speicherplatz-Hotspots

•
Home-Verzeichnisse Audit

•
Projekt-Verzeichnisse Lifecycle

5. CISO Berichte (20 Prompts)

Compliance-Bewertungen und Executive Reports für Sicherheitsverantwortliche.

Beispiel-Themen:

•
NIS2 Compliance Assessment

•
BSI IT-Grundschutz Bewertung

•
ISO 27001 Access Control

•
HIPAA Security Rule

•
Privileged Access Management

•
Segregation of Duties

•
Identity Governance Maturity

6. Entra ID (20 Prompts)

Analyse der Azure AD / Entra ID Integration und Cloud-Identitäten.

Beispiel-Themen:

•
Synchronisierungsstatus

•
Hybrid Identity Konfiguration

•
Gastbenutzer Governance

•
Application Permissions

•
Conditional Access Coverage

•
Lizenzzuweisung

•
B2B Collaboration

7. Teams (20 Prompts)

Microsoft Teams Governance und Compliance-Analysen.

Beispiel-Themen:

•
Teams Governance

•
Teams ohne Eigentümer

•
Channel Proliferation

•
Guest Access in Teams

•
Lifecycle Policy Compliance

•
Sensitivity Labels

•
Meeting Policies

8. Obsolete Accounts (20 Prompts)

Identifikation und Cleanup von inaktiven und verwaisten Objekten.

Beispiel-Themen:

•
Inaktive User-Konten

•
Deaktivierte Konten mit Berechtigungen

•
Nie angemeldete Konten

•
Verwaiste Computer-Objekte

•
Test- und Demo-Konten

•
Ungenutzte Service-Accounts


