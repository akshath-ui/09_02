# Smart Fishing Harbour Information System – Kerala 2026 🌊

![Status](https://img.shields.io/badge/Status-Hackathon_Ready-brightgreen) ![Tech Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3%20%7C%20JS-blue) ![Challenge](https://img.shields.io/badge/Challenge-2_Smart_Fishing_Harbour-0066cc) ![IBM Bob](https://img.shields.io/badge/Built_with-IBM_Bob-00a86b)

A comprehensive, mobile-first web application built for the **KeralAI Grand Challenge 2026 (Challenge 2)**. This platform acts as a unified "Smart City OS" for Kerala's coastal fishing harbours, digitizing operations and providing real-time data to all stakeholders.

---

## 📸 Project Showcase
<div>
  <img width="1920" height="1080" alt="Screenshot (289)" src="https://github.com/user-attachments/assets/62ee9444-6a95-446a-b718-e95f935aabbc" />
<img width="1920" height="1080" alt="Screenshot (287)" src="https://github.com/user-attachments/assets/8364e178-3f40-42db-9305-dc6f7de60bb4" />
<img width="1920" height="1080" alt="Screenshot (286)" src="https://github.com/user-attachments/assets/9b0bf0ba-2b86-46fd-8285-fd8b58465fca" />


</div>

---

## 🌊 The Problem
Fishermen arriving at harbours often lack real-time information regarding:
- Which fish species are fetching the best prices locally versus at nearby harbours.
- Availability of crucial resources like ice plants and cold storage.
- Active buyers and immediate market demand.

By the time this information is acquired manually, valuable time and potential income are lost.

---

## 💡 The Solution
The **Smart Fishing Harbour Information System** is a real-time dashboard connecting fishermen, traders, harbour management, and auction operators into a single, synchronized ecosystem. 

### 🎭 Six Distinct User Roles
The application features a dynamic role-switching architecture, instantly adapting the UI, navigation, and data presentation based on the user persona:

1. 🚤 **Fisherman:** Access live fish prices, compare market trends via charts, track ice plant capacity, and receive weather notices.
2. 🐟 **Fish Customer:** Search for available fresh catch using budget filters, view sea conditions, and find verified nearby sellers.
3. 🏗️ **Harbour Maintenance:** Manage a task board for infrastructure issues (e.g., broken dock gates, ice machine failures) categorized by priority.
4. 🔨 **Auction Owner:** Manage live bidding wars with real-time countdown timers, track available fish lots, and review transaction histories.
5. 🏛️ **Harbour Authority (Admin):** Monitor high-level KPIs (boats at sea, total daily revenue) and utilize an emergency broadcast system for instant alerts.
6. 🚚 **Fish Vendor/Trader:** Track active wholesale orders, view wholesale vs. retail price comparisons, and participate directly in live harbour auctions.

---

## 🚀 Key Technical Highlights
- **Zero-Dependency Architecture:** Runs entirely on standard HTML5, CSS3, and Vanilla JavaScript within a single file (`ASIETmechboys_challenge2_2.html`). No build step or backend required for the demo.
- **Mobile-First Design:** Fully responsive layout with bottom-tab navigation tailored specifically for mobile devices used by fishermen at sea.
- **Integrated AI Assistant:** Features "Harbour Helper," a simulated chatbot that answers natural language queries about fish prices, auction timings, and weather conditions.
- **Data Visualization:** Utilizes **Chart.js** to render interactive price trend line graphs and harbour comparison bar charts.
- **Localization Ready:** Built-in framework for switching between 10 regional languages (including Malayalam, Hindi, and English).
- **Theming:** Includes a fully functional Dark/Light mode toggle that adapts charts and UI elements instantly.

---

## 🛠️ Usage
1.  Clone this repository to your local machine:
    ```bash
    git clone [https://github.com/akshath-ui/09_02.git](https://github.com/akshath-ui/09_02.git)
    ```
2.  Navigate to the directory:
    ```bash
    cd 09_02
    ```
3.  Open the `ASIETmechboys_challenge2_2.html` file in any modern web browser (Google Chrome, Firefox, Safari, Edge).

---

## 🤝 IBM Bob Integration
This project was conceptualized and architected using the **IBM Bob** AI-powered SDLC platform. Bob's Agent and Ask modes were utilized to structure the component layout, generate the CSS styling (including the animated canvas background), and scaffold the interactive mock data models.
