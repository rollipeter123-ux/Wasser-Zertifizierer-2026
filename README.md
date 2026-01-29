💧 Wasserwissen 2026 - PFAS Radar & Intelligence Platform

"Die wissenschaftliche Autorität für Trinkwasseroptimierung"

Dieses Repository enthält den Quellcode für Wasserwissen 2026, eine hochkonvertierende SaaS-Plattform zur Analyse von Trinkwasserdaten, spezialisiert auf die neue EU-Trinkwasserrichtlinie 2026 und PFAS-Belastungen.

🚀 Features

Die Plattform vereint Datenvisualisierung, KI-Analyse und E-Commerce-Elemente in einer performanten Single-Page-Application (SPA).

🗺️ PFAS-Radar (Live-Map): Interaktive Karte (Leaflet.js) mit simulierten Echtzeit-Datenpunkten und Heatmap-Visualisierung für industrielle Belastungszonen.

🤖 HydroBot AI: Integrierter Chatbot (Gemini API Ready) für automatisierte Kundenberatung und Sales-Steuerung.

📊 Risiko-Dashboard: Interaktive Charts (Chart.js) zur Visualisierung von Grenzwerten, historischen Trends und Chemikalien-Mix.

💰 ROI-Simulator: Dynamischer Kostenrechner (Slider-basiert) zum Vergleich von Flaschenwasser vs. Filtersystemen.

⚖️ Legal-Generator: Client-seitige Erstellung von PDF-Dokumenten (jsPDF) für Mieter (Vermieter-Anschreiben, Genehmigungen).

🛒 Affiliate-Optimierung: Psychologisch optimierte Conversion-Pfade zu High-Ticket-Partnerprodukten (AquaZero, Lotus Vita).

🛠️ Tech Stack

Das Projekt wurde als "No-Build" SPA konzipiert, um maximale Portabilität und einfaches Hosting zu gewährleisten.

Core: HTML5, Modern JavaScript (ES6+)

Styling: Tailwind CSS (via CDN für Instant-Prototyping)

Mapping: Leaflet.js + OpenStreetMap

Charts: Chart.js

PDF-Generation: jsPDF

Icons: FontAwesome 6

📦 Installation & Nutzung

Da es sich um eine statische Anwendung handelt, ist keine komplexe Installation notwendig.

Repository klonen:

git clone [https://github.com/dein-username/wasserwissen-2026.git](https://github.com/dein-username/wasserwissen-2026.git)


Starten:
Öffne einfach die Datei PFAS_Radar_Ultimate_SaaS.html (oder index.html) in einem modernen Browser.

Deployment (Optional):
Das Projekt ist "Ready for Vercel/Netlify". Einfach das Repo verbinden und deployen.

⚙️ Konfiguration

Um die KI-Features und Live-Suchdaten zu aktivieren, müssen in der index.html (bzw. HTML-Datei) folgende Konstanten befüllt werden:

// Zeile ~990 im Code
const GEMINI_API_KEY = "DEIN_GEMINI_KEY"; 
const GOOGLE_SEARCH_CX = "DEINE_SEARCH_ENGINE_ID"; 
const GOOGLE_SEARCH_API_KEY = "DEIN_SEARCH_KEY"; 


Hinweis: Ohne API-Keys läuft die Anwendung im Simulations-Modus (Demo-Daten), was für Präsentationen ideal ist.

📈 Conversion-Strategie

Die Seite folgt einem strikten "Fear-Solution-Funnel":

Trigger: Lokale Risiko-Analyse (PLZ-Eingabe).

Agitation: Visualisierung der Gefahr (Radar & Grenzwerte).

Solution: Wissenschaftlich fundierte Lösungsvorschläge (Filter).

Rationalization: Kostenrechner & Rechtssicherheit (Mieter-Hub).

© 2026 Wasserwissen Institut. Entwickelt für High-End Affiliate Marketing.
