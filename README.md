# **A Front-End Learning Lab Final Project 2024**
A responsive information website about Solo city, featuring culinary spots, tourist destinations, events, and an interactive map. Built with HTML, TailwindCSS, vanilla JavaScript, and LeafletJS.

## 🚀 Overview
This project presents curated information about Solo in a simple and interactive interface. Users can browse places, filter by category, sort by name, search in real time, and explore locations through a map powered by LeafletJS. The website is designed to be lightweight, fast, and usable on both desktop and mobile.

## ✨ Features
**1. Responsive UI (TailwindCSS)**
- Fully responsive layout
- Modern card-based design
- Utility-first classes for consistent styling
**2. Real-Time Search**
- Instantly filter content by keywords
- Matches name, category, and description
**3. Category Filters**
- Show only:
   Kuliner
   Wisata
   Event
or all categories
- Uses data-category attributes for simple logic
**4. Sorting Options**
- Default
- Name A → Z
- Name Z → A
- Sorting applied without reloading the page
**5. Interactive Map (LeafletJS)**
- Displays markers for culinary spots, tourist places, and events
- Uses OpenStreetMap tiles
- Lightweight and easy to extend for more locations
**6. Smooth Navigation & Sticky Header**
- Easy jump between sections
- Header stays visible while scrolling

## 🛠 Tech Stack
| Layer         | Technology                    |
| ------------- | ----------------------------- |
| Structure     | **HTML5**                     |
| Styling       | **TailwindCSS (CDN)**         |
| Interactivity | **Vanilla JavaScript**        |
| Mapping       | **LeafletJS + OpenStreetMap** |
| Assets        | Static images                 |

## 🔍 How It Works
### 1) Filtering
Each card has:
```
<div class="card" data-category="kuliner"></div>
```
JavaScript checks this value and hides/shows cards when the user clicks filter buttons.
### 2) Search
Works by reading the input field and comparing it to:
      - title
      - description
      - category
### 3) Sorting
Uses array sorting on DOM elements before rendering them back into the container.
### 4) Map
```
L.marker([lat, lng]).addTo(map)
```
Each location is added manually or can be loaded from JSON in a future update.
