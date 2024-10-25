# Anforderungen
Gewünscht ist eine Exceltabelle, die eine Übersicht über alle Übernachtungsaufenthalte von Person X beinhaltet und die sich aus Daten aus dem Profil von X auf Booking.com speist. Die Übersicht soll durchsuchbar, filterbar und übersichtlich sein und nur die nötigsten Informationen enthalten.

# Beschreibung des Extraktionsvorgangs
Die Daten, die gesichert werden sollen, befinden sich auf zwei Webseiten:
1. “Bookings & Trips”  beinhaltet eine Übersicht über alle Bookings und fasst diese in Trips zusammen. Jeder Bookingeintrag verweist auf eine “Booking Confirmation”.
2. “Booking Confirmation” beinhaltet alle Informationen zu einem Booking.

In einem ersten Schritt soll von “Bookings & Trips” eine Übersicht über alle Bookings samt der dazugehörigen Metadaten extrahiert werden.

Für ein Booking sind das:
* der Link zur “Booking Confirmation”
* der Hotelname
* der Aufenthaltszeitraum
* der Ort
* der Durchführungsstatus

Hieraus ergibt sich eine Liste mit Links zu den einzelnen “Booking Confirmation”s. In einem zweiten Schritt soll für jedes Booking die “Booking Confirmation" aufgerufen und von dort die folgenden Informationen extrahiert werden:
* Buchungsnummer
* Adresse des Hotels
* GPS-Koordinaten des Hotels
* Das Check-In-Datum
* Das Check-Out-Datum
* Anzahl der gebuchten Zimmer
* Bruttopreis der Buchung

Zusätzlich sollen zu den gebuchten Zimmern einer “Booking Confirmation" folgende Informationen extrahiert werden:
* Zimmerkategorie
* Namen der Gäste, für die das Zimmer gebucht wurde
* Ob Verpflegung inklusive war

# Beschreibung des Produkts
- Eine Excel-Arbeitsmappe, die 
    - eine Auswertetabelle, welche die Anzahl an Übernachtungen pro Jahr und Land anzeigt, sowie die Übernachtungskosten pro Jahr
    - eine Übersichtstabelle mit den Spalten Buchungsnummer, Ort, Hotel, Von, Bis, Zimmer, Preis
    - eine Detailansicht mit den Spalten Buchungsnummer, Von, Bis, Hotel, Adresse, Ort, GPS, Status, Zimmerkategorie, Gäste, Verpflegung 
- HTML-Sicherungen der Webseiten zur Dokumentation des Quellenmaterials
- Screenshots der Webseiten zum Einfügen in Akten
- Hash-Werte zur Dokumentation der Unveränderlichkeit des Quellenmaterials
