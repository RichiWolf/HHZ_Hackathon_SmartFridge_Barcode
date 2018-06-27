# HHZ_Hackathon_SmartFridge_Barcode

<a href="https://github.com/RichiWolf/HHZ_Hackathon_SmartFridge_Barcode/wiki"> 1. Home </a>  
<a href="https://github.com/RichiWolf/HHZ_Hackathon_SmartFridge_Barcode/wiki/2.-Service-Architektur-nach-Elgar-Fleisch">2. Service Architektur nach Elgar Fleisch</a>  
<a href="https://github.com/RichiWolf/HHZ_Hackathon_SmartFridge_Barcode/wiki/3.-Konzepte-und-Einbettung">3. Konzepte und Einbettung</a>
<a href="https://github.com/RichiWolf/HHZ_Hackathon_SmartFridge_Barcode/wiki/4.-Versuche">4. Versuche</a>
<a href="https://github.com/RichiWolf/HHZ_Hackathon_SmartFridge_Barcode/wiki/5.-Design-Prinzipien">5. Design Prinzipien</a>
<a href="https://github.com/RichiWolf/HHZ_Hackathon_SmartFridge_Barcode/wiki/6.-Bewertung-des-Gesch%C3%A4ftsmodells">6. Bewertung des Geschäftsmodells</a>
<a href="https://github.com/RichiWolf/HHZ_Hackathon_SmartFridge_Barcode/wiki/7.-Ergebnisse-des-Hackathons">7. Ergebnisse des Hackathons</a>
<a href="https://github.com/RichiWolf/HHZ_Hackathon_SmartFridge_Barcode/wiki/8.-Teammitglieder-und-Organisation">8. Teammitglieder und Organisation</a>



Dieses Projekt entstand im Rahmen des zweitägigen Hackathons des Master-Studiengangs "Services Computing" am Herman Hollerith Zentrum in Böblingen. Der Hackathon verfolgt das Ziel, verschiedene "Internet of Things" Ansätze im Bereich "Lernen und Lehren" und "Smart Home" zu testen und einen ersten MVP (Minimum Viable Product) zu erstellen. Als Ergebnis der Projekte soll eine Machbarkeitsstudie der Serviceidee, Einsatzmöglichkeiten sowie eine Konzeptbeschreibung  hervorgehen.

 

# Beschreibung des Services
Die Serviceidee beschäftigt sich mit der automatischen Befüllung einer digitalen Einkaufsliste, welche über eine App aufgerufen werden kann. Dies erspart dem Anwender die Bestandsüberwachung von regelmäßig genutzten Produkten. Ermöglicht wird der Service durch die Anbringung einer oder mehrerer Kameras im oder außerhalb des Kühlschranks. Mithilfe der Kameras soll der Barcode der herausgenommenen sowie zurückgestellten Produkte erfasst werden. Eine Barcode-Erkennungs-Software ermöglicht das Auslesen des Barcodes, um das jeweilige Produkt zu identifizieren. Wird ein Produkt herausgenommen und nicht wieder in den Kühlschrank zurückgelegt, wird es automatisch in die digitale Einkaufsliste aufgenommen. 

Um ein energiesparendes System zu gewährleisten, sollen die Kameras nur aktiviert werden, solange der Kühlschrank geöffnet ist. Das hat den zusätzlichen Vorteil, dass weniger nicht verwertbare Bilder entstehen, die ansonsten aussortiert werden müssten.

Aufgrund der zeitlichen Begrenzung des Hackathons auf zwei Tage, ist eine vollständige Umsetzung der Serviceidee nicht möglich. Aus diesem Grund wird im Rahmen des Projekts eine Machbarkeitsstudie durchgeführt.  
Hierfür werden zum einen verschiedene Kamerapositionen im und um den Kühlschrank herum evaluiert. Dazu wird statistisch geprüft, wie oft und wie gut der Barcode auf den generierten Bildern zu sehen ist.  
Zum anderen erfolgt eine Bewertung von verschiedenen Softwarelösungen zur visuellen Erkennung von Barcodes.


# Value Proposition Canvas

Das von Osterwalder entwickelte Value Proposition Canvas wurde im Rahmen dieses Projektes verwendet, um den Nutzen für den Kunden zu identifizieren. Daraus ist folgendes Canvas entstanden:

![Value Proposition Canvas](https://github.com/RichiWolf/HHZ_Hackathon_SmartFridge_Barcode/blob/master/VPC.png)

Der im Canvas beschriebene Service ermöglicht dem Nutzer seine Einkäufe mithilfe der automatisch erzeugten Einkaufsliste zu erledigen. Der Kunde spart sich die Zeit eine manuelle Einkaufsliste anzufertigen, vermeidet Fehleinkäufe und kann die Informationen überall über sein Smartphone abrufen.

Das folgende Erklärvideo liefert zusätzliche Informationen über den Nutzen und der Funktionsweise der Serviceidee: [Simple Show](https://videos.mysimpleshow.com/0aCBUDVING)
