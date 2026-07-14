# House-Renovation-Progress-Tracker
A lightweight, high-performance vanilla JavaScript web application tailored for real estate flippers, investors, and contractors. This system calculates investment metrics using the standard 70% rule, manages multi-room checklists, logs real-time chronologies, and processes hardware inventory labels via client-side automated scanners. 
## 📅 Release & Version Metadata
*   **Current Production Status**: Production Stable (PWA Installable)
*   **Architecture Track**: Vanilla ES6+ Sourcing / Decoupled Data Handshakes
*   **Compiled Repository Release**: July 2026
## Built With
*   [jszip][cdnjs.cloudflare.com] - A library for creating, reading, and editing .zip files with Javascript.
*   [Tesseract.js][jsdelivr.net] - Pure Javascript OCR for more than 100 languages
## Core Architecture & Features
### Keystroke-Reactive Financial Engine
   Analyzes user input as they input Purchase Price, Renovation Budget, After Repair Value, and Holding Timeline. 
   Utilizes several hidden values to calculate Net-Profit along with user inputed data
   Compliant with 70% Rule Metrics
### Cross-Device Mobile Calibration
   Custom @media viewport grid overrides that dynamically shift layout cards into clean side-to-side columns on desktops, but stacks input boxes into vertical, tap friendly targets on smartphones. 
   Hardware Canvas Compressors: converts smartphone camera photographs to lightweight base64 thumbnail, pushing data into browser memory pools, and preventing database storage crashes. 
### Zip Folder Archiver
   The zip folder comes with a spread sheet, a scraped webpage built from the individual house card information and permanetly expanded for viewing. Images are stored seperately but the html provides direct more in line view of where those images go.  
   Html page generated using webscrapping, Accounting-ready Excel spreadsheet and folder containing all images stored locally for the house being exported.  
### Global Line Item Editting
   Enables user to update line items utilizing .csv or after updating individual values as you add items to repair list. 
### Image Scanner
   Detects letters in images using Tesseract.js.
   
## System Data Schema Blueprint
{
  "id": 1719284210452,  
  "name": "Oak Street Modern Duplex",  
  "location": "123 Oak St, Carrollton, TX",  
  "purchasePrice": "150000",  
  "renovationBudget": "40000",  
  "arv": "275000",  
  "timelineMonths": "6",  
  "rooms": ["Kitchen", "Bathroom-1", "Living Room"],  
  "tasks": [  
    {  
      "id": 1719284311099,  
      "title": "Install Custom Backsplash",  
      "lineItem": "Tile Installation",  
      "room": "Kitchen",  
      "roomNum": null,  
      "subgroup": "Plumbing",  
      "cost": 450.00,  
      "qty": 1,  
      "unit": "ea.",  
      "completed": false,  
      "image": "data:image/jpeg;base64,...",  
      "serialNumbers": ["JABCINERS456785"]  
    }  
  ],  
  "notes": [  
    {  
      "id": 0,  
      "about": "Reaction",  
      "note": "Auto-OCR: Captured unique device serial tokens: JABCINERS456785"  
    }  
  ]  
}  
## Technology & Build Stack
*   **Logic Engine**: Pure Vanilla JavaScript (ES6+) leveraging parallel array destructuring, control-flag execution bypass channels (`skipRender`), and asynchronous promise lifecycles.
*   **Interface Layer**: Semantic HTML5 markup and responsive CSS Flexbox/Grid modules utilizing custom theme design properties for cohesive component formatting.
*   **Storage Framework**: Browser `localStorage` serialization strings (`groupHousesMedia`).
*   **External Packages**: Distributed JSZip compression streaming and Tesseract.js computer vision worker arrays.
## How To Run Locally
### run on: https://gmw93.github.io/House-Renovation-Progress-Tracker/
### Android Chrome
   1. tap the 3 dots at top of screen
   2. scroll down action list drawer and look for "Add to Home Screen" or "Install App"
   3. Tap it, and click Install
### iOS Safari
   1. very bottom toolbar and tap share icon (square with arrow pointing up)
   2. scroll down action list and tap "add to home screen"
### Desktop
   1. Clone Repository directly down onto your local workspace environment
   2. Double-click root 'index.html' file inside your explorer panel to fire up system in any standard modern web browswer
### All Above Require
   All above require input of csv file, to set data for future usage
   1. Category, Task Name, Cost (per unit), Unit (measure), Subgroup 
   2. Kitchen, Install Kitchen Object, $0.0, ea., Cabintry 
