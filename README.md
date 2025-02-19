﻿# Anime Scraper

Un web scraper moderno che aggrega contenuti da AnimeWorld e LiveChart, costruito con Python/Flask e un'interfaccia utente minimalista ispirata a Swift/XCode.

## 🚀 Caratteristiche Tecniche

### Backend (Python/Flask)
- Web scraping avanzato con `cloudscraper` per bypassare protezioni anti-bot
- Sistema di caching per ottimizzare le richieste
- Gestione degli errori e logging dettagliato
- API RESTful per la gestione dei dati degli anime

### Frontend (HTML/CSS/JavaScript)
- Design responsive ottimizzato per mobile e desktop
- Interfaccia utente minimalista in stile Swift/XCode
- Scroll orizzontale fluido con snap points
- Lazy loading delle immagini per prestazioni ottimizzate

### Sezioni Principali
1. **Più Popolari**: Scraping da `animeworld.so/filter?sort=6`
2. **Ultime Uscite**: Scraping da `animeworld.so/newest`
3. **Calendario Giornaliero**: Integrazione con `livechart.me/schedule`
4. **Ultimi Episodi**: Scraping da `animeworld.so/updated`

## 🛠 Tecnologie Utilizzate

- **Backend**:
  - Python 3.x
  - Flask
  - BeautifulSoup4
  - Cloudscraper
  - Logging

- **Frontend**:
  - HTML5
  - CSS3 (CSS Variables, Flexbox, Grid)
  - JavaScript (ES6+)
  - Font Awesome
  - SF Pro Display Font

## 📱 Responsive Design

- Layout fluido che si adatta a diverse dimensioni dello schermo
- Breakpoints ottimizzati per:
  - Desktop (> 768px)
  - Tablet (≤ 768px)
  - Mobile (≤ 480px)
- Controlli touch-friendly su dispositivi mobili

## 🔍 Funzionalità di Ricerca

- Ricerca in tempo reale degli anime
- Risultati formattati in cards responsive
- Gestione degli errori e stati di caricamento

## 🎨 UI/UX Features

- Tema scuro moderno
- Animazioni fluide
- Scroll orizzontale con controlli intuitivi
- Cards con hover effects
- Loading states e gestione errori

## 📦 Struttura del Progetto
La struttura del progetto è organizzata come segue:
- `static/`: Contiene i file statici
  - `css/`: Stili CSS
  - `js/`: Script JavaScript
- `templates/`: Contiene i template HTML
- `app.py`: File principale dell'applicazione Flask

## 🚀 Performance

- Lazy loading delle immagini
- Caching dei dati
- Ottimizzazione delle richieste API
- Gestione efficiente dello scroll
