# Timeline Dante – Visualizzazione Interattiva

## Descrizione
Questo progetto consiste in un portale web dedicato alla visualizzazione dei personaggi della *Divina Commedia*, con un focus iniziale sui canti dell’Inferno.  
Il sito integra filologia e tecnologie web, proponendo una timeline interattiva (basata su **TimelineJS**) che consente di esplorare i personaggi in relazione al loro contesto storico, arricchita da una tabella e una mappa concettuale.

---

## Struttura del Progetto
- **index.html** – Homepage e introduzione al progetto.  
- **timeline.html** – Visualizzazione interattiva con TimelineJS.  
- **table.html** – Tabella dei personaggi, con ordinamento e ricerca.  
- **map.html** – Mappa concettuale e struttura del portale.  
- **convert.html** – Tool per convertire file CSV (da Google Sheets) in JSON compatibile con TimelineJS.  
- **/data/timeline.json** – Dati principali dei personaggi.  
- **/assets/** – Contiene CSS, immagini, font e icone.  

---

## Metadati
Ogni pagina HTML include i **meta tag Dublin Core** (es. `title`, `creator`, `description`, `date`, `rights`) per documentare le risorse e facilitarne la condivisione.  
Il file `timeline.json` è conforme allo schema di Knight Lab, ma arricchito con campi personalizzati come **`condizioneMorale`**, che consente la classificazione dei personaggi per peccato, vizio o virtù.

---

## Tecnologie
- **HTML5, CSS3, JavaScript**  
- **Bootstrap 5** – Layout responsivo  
- **TimelineJS (Knight Lab)** – Timeline interattiva  
- **DataTables.js** – Tabella con paginazione e ricerca  
- **Google Sheets (CSV)** – Creazione dati di input  

---
