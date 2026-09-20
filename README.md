> 1st Place Hackathon Winner – Booking.com Challenge (Hack4Her 2026, Eindhoven)

> This website was created as part of **hack4her 2026** in Eindhoven where the main objective was to come up with a solution designed to empower female solo travellers and enhance their security while exploring the world. 
> Engineered as a direct feature concept for **Booking.com**, this prototype demonstrates how safety insights, community trust, and seamless UI integration can transform the solo travel experience. 
>The project was awarded **1st Place** in the official Booking.com Challenge track.


# SafeTravel ·  Booking.com 

**SafeTravel** is a mobile-first web application designed to empower travelers, especially solo female and safety-conscious travelers with real-time safety insights, interactive neighborhood safety maps, automated arrival check-ins, and an AI powered safety companion.


##  Features

### 1. Before Booking (Property & Safety Insights)
* **Property Safety Score**: View data-backed safety scores (0–100) calculated from verified traveler reviews, crime indices, night lighting, and transit availability.
* **Safety Breakdown**: Detailed sub-scores for review sentiment, area crime, night safety, transport safety, solo female ratings, staff responsiveness, and lighting/CCTV.
* **Review Insights**: Micro-badges highlighting property highlights and potential warnings (e.g., *"Solo female friendly"*, *"24hr staffed desk"*, or *"Nightlife area – be aware"*).
* **Trust & Methodology Transparency**: Explanations on how safety scores are calculated using thousands of guest ratings and local authority crime data.

### 2. After Booking (Safety Guide & Interactive Heatmap)
* **Customized AI Safety Briefings**: Location-specific safety tips tailored to your destination city.
* **Emergency Directory**: One-touch access to local emergency services (e.g., EU 112), local police lines, safe taxi services, and direct hotel contact numbers.
* **Safe Transport Directory**: Ratings and recommendations for local transport options (apps, public transit, bike-shares, and night buses).
* **Interactive Safety Heatmap**: An SVG-rendered interactive map of the city showing safety zones (Safe, Moderate, Caution), hotel locations, transit hubs, and emergency medical services with interactive tooltips.

### 3. Safe Arrival Check-In (Premium Feature)
* **Arrival Tracking**: Set a destination and expected arrival time (ETA).
* **Automated Safety Check-In**: Confirm safe arrival with a single tap to automatically notify your designated trusted contacts.
* **Flexible Window Extension**: Easily extend your check-in timer (15 min to 2 hours) if delayed.
* **Emergency Escalation**: Trigger instant emergency alerts sharing your status and last-known location with trusted contacts.

### 4. SafeStay AI Companion (Interactive Chatbot)
* **Review Intelligence**: Chat directly with an AI companion trained on guest safety reviews.
* **Preset Queries**: Quick-launch buttons for common safety questions:
  * *"Is this hotel safe for solo female travelers?"*
  * *"What concerns appear most often in reviews?"*
  * *"Can I safely walk here at night?"*
  * *"What transport should I use after midnight?"*
  * *"I feel unsafe — what should I do?"*
* **Dynamic Follow-Ups**: Powered by Anthropic's Claude API for personalized follow-up safety advice.


## Technology Stack

* **Frontend**: Single-file HTML5, CSS3 (Custom Variables, Flexbox, Grid), and Vanilla JavaScript.
* **Typography**: Google Fonts (`DM Sans` & `DM Serif Display`).
* **Mapping**: Lightweight inline SVG-based interactive map rendering.
* **AI Integration**: Anthropic Claude API (`claude-sonnet-4-6`) integration for real-time natural language responses.
* **Data Layer**: Embedded JSON data structure containing structured hotel and safety review metadata across global destinations.
