# 🌍 Countries Explorer

## 🌐 Live Demo

🔗 https://frontend-countries-api-project.netlify.app/

A production-style React single-page application for exploring global country data using the REST Countries API.  

This project focuses on building a clean, scalable frontend architecture with real-world features like dynamic routing, state-driven UI, API integration, and responsive design.

---

## 🚀 Key Features

- Fetches and displays country data from REST Countries API
- Real-time search by country name
- Region-based filtering (Africa, Americas, Asia, Europe, Oceania)
- Detailed country view with rich metadata:
  - Native name, population, region, subregion
  - Capital, currencies, languages, top-level domain
- Border country navigation for seamless exploration
- Light/Dark mode with persistent user preference (localStorage)
- Skeleton loading UI for better user experience
- Graceful error handling for invalid routes or data

---

## 🧠 Key Highlights

- Component-driven architecture with reusable UI blocks
- Clean routing structure using React Router (list → detail navigation)
- Context API for global theme management
- Custom hooks for logic abstraction (filters, theme, window size)
- Focus on UX with non-blocking loading states (shimmer UI)
- Designed with scalability and maintainability in mind

---

## 🛠 Tech Stack

- React 18
- React Router DOM 6
- Parcel 2
- CSS (modular/component-based)
- REST Countries API (external)
- Font Awesome (icons)
- Google Fonts (Nunito)

---

## ⚙️ Installation & Setup

### Prerequisites
- Node.js 18+
- npm

### Run Locally

```bash
git clone https://github.com/nikhil-barve1/countries_api.git
cd countries_api
npm install
npm start
```

App runs at:
```
http://localhost:1234
```

---

## 📌 Usage

- Browse all countries on the home page
- Search countries by name
- Filter countries by region
- Click any country to view detailed information
- Navigate across neighboring countries via border links
- Toggle between light and dark themes

---

## 📁 Project Structure

```text
components/      → UI components (cards, filters, detail views)
contexts/        → Global state (ThemeContext)
hooks/           → Custom hooks (filtering, theme, utilities)
public/          → Static assets and routing config
App.jsx          → Root component
index.jsx        → Entry point
```

---

## 🔮 Future Improvements

- Debounced search for performance optimization
- URL-based filters (shareable state)
- API caching for faster navigation
- Unit & integration testing (RTL / Jest)
- Accessibility improvements (ARIA, keyboard navigation)
