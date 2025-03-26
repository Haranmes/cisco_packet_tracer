# Webdesign & Marketing Soliman

## Über "Webdesign & Marketing Soliman GmbH"

### Unternehmensgegenstand

Die Webdesign & Marketing Soliman GmbH ist ein innovatives Dienstleistungsunternehmen, das sich auf die Entwicklung und Umsetzung digitaler Medienlösungen spezialisiert hat. Als GmbH strukturiert, konzentriert sich das Unternehmen auf zwei strategisch wichtige Hauptgeschäftsfelder. Im Bereich Webdesign und Webentwicklung bietet das Unternehmen die Entwicklung von High-Performance Websites mit excellentem SEO-Score, Responsive Design für optimale Darstellung auf allen Endgeräten, moderne UI/UX-Konzepte für maximale Benutzerfreundlichkeit, Content Management Systeme (CMS) für einfache Pflege sowie regelmäßige Performance-Optimierung und Wartung an.

Im zweiten Hauptgeschäftsfeld, dem digitalen Marketing, liegt der Fokus auf Suchmaschinenoptimierung (SEO) für Top-Rankings, Social Media Marketing und Community Management, Content Marketing und Storytelling, E-Mail Marketing Kampagnen sowie Analytics und Conversion-Optimierung.

### Unternehmensaufbau

Die Firma zeichnet sich durch eine effiziente, dreigliedrige Organisationsstruktur aus:

Die Geschäftsführung ist mit modernster mobiler Technologie wie High-End Laptops und aktuellen Smartphones ausgestattet, um optimale Erreichbarkeit und Flexibilität zu gewährleisten. Die professionelle Webdesign-Abteilung besteht aus hochqualifizierten Webdesignern, die an ergonomisch gestalteten Arbeitsplätzen arbeiten. Diese ist eng mit einem erfahrenen Marketing-Team verbunden, wodurch eine ganzheitliche Projektbearbeitung ermöglicht wird.

### Unternehmensgröße

Als dynamisches mittelständisches Unternehmen verfügt die Firma über ein effizientes Team von 5-10 hochspezialisierten Mitarbeitern, die in einer modernen Bürostruktur eng zusammenarbeiten. Das innovative Kombibüro-Konzept mit verschiedenen Fachabteilungen fördert dabei die Kommunikation und Kreativität zwischen den Mitarbeitern. Ein Beispiel Kundenauftrag für die Bäckerei "Sweet Delights", eine Bäckerei mit amerikanischen Backwaren:

![image.png](image.png)

---

## Über das Netzwerk

Die Netzwerkinfrastruktur des Unternehmens basiert auf mehreren Kernkomponenten. Im Zentrum steht ein DNS & DHCP Server, der die grundlegenden Netzwerkdienste bereitstellt. Die räumliche Gestaltung als Kombibüro ermöglicht eine enge Zusammenarbeit zwischen den Webdesign- und Marketing-Teams. Für maximale Flexibilität wurde eine mobile Geräteanbindung implementiert, die es den Mitarbeitern ermöglicht, von verschiedenen Standorten aus zu arbeiten. Zusätzlich verfügt das Unternehmen über eine professionelle Webserver-Struktur zur Verwaltung und Bereitstellung der Kundenaufträge.

### Namenskonzept

In der "Webdesign & Marketing Soliman GmbH" entsprechen die Namen der Geräte im Netz ihrer physischen Lage im Bürogebäude bspw. `OFFICE_1F` oder bei Endgeräten → Art des Endgerätes + Bereich wie bspw. `PC_EMPFANG`. Dies ermöglicht bei einer Vielzahl von Geräten eine schnelle Lokalisierung jedes einzelnen Geräts.

### Zugangsdaten

| Bezeichnung | WIFI_SSID | Privileged EXEC | Konsolenport | Domaine | User | Passwort | WLAN PW |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CENTRAL_MULTILAYER | - | CENTRAL_MULTILAYER | multilayer | eg.de | admin | web | - |
| OFFICE_1F | - | OFFICE_1F | 1floor | 1floor.de | admin | web | - |
| OFFICE_2F | - | OFFICE_2F | 2floor | 2floor.de | admin | web | - |
| CENTRAL_R1 | - | central | centralr1 | centralr1.de | admin | web | - |
| WIFI_1F | WIFI_1F | - | - | - | - | - | WIFI1FLOOR |
| WIFI_2F | WIFI_2F | - | - | - | - | - | WIFI2FLOOR |

### Netztopologie

![image.png](image%201.png)

## Adressierungstabelle

| Gerätename | Interface | IPv4-Adresse/DHCP | Subnetzmaske | Default Gateway |
| --- | --- | --- | --- | --- |
| CENTRAL_R1 | G0/0 | 192.168.1.254 | 255.255.255.0 | - |
| SERVER_CENTRAL | F0 | 192.168.1.253 | 255.255.255.0 | - |
| OFFICE_EG | VLAN1 | 192.168.1.252 | 255.255.255.0 | 192.168.1254 |
| OFFICE_1F | VLAN1 | 192.168.1.251 | 255.255.255.0 | 192.168.1.254 |
| OFFICE_2F | VLAN1 | 192.168.1.250 | 255.255.255.0 | 192.168.1.254 |
| LAPTOP_CEO | F0 | DHCP | 255.255.255.0 | - |
| IPhone_CEO | W0 | DHCP | 255.255.255.0 | - |
| PC_EMPFANG | F0 | DHCP | 255.255.255.0 | - |
| IPhone_MARKETING | W0 | DHCP | 255.255.255.0 | - |
| PC_MARKETING | F0 | DHCP | 255.255.255.0 | - |
| PC_WEBDESIGNER | F0 | DHCP | 255.255.255.0 | - |
| IPhone_webdesigner | W0 | DHCP | 255.255.255.0 | - |
| CENTRAL_R1 | G0/1 | 10.0.0.1 | 255.255.255.0 | - |
| dns.sinsheim | F0 | 10.0.0.2 | 255.255.255.0 | - |
| sweetdelights.webserver | F0 | 10.0.0.3 | 255.255.255.0 | - |
