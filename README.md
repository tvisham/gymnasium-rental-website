# JHS Gymnasium Rental Website

A multi-page website for renting a high school gymnasium as an event venue: browse upcoming events, buy tickets, request a booking, and check venue policies. Built for an FBLA website design competition.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

![Home page](docs/gym-home.png)

## Pages

| Page | What's there |
|---|---|
| **Home** | Image carousel, featured events, call to action |
| **Events & Tickets** | Nine upcoming events, each with its own detail page and a ticket purchase pop-up |
| **Event Booking** | Venue features (3,500-seat capacity, sound, kitchen, accessibility) and a booking request form |
| **Venue Information** | Policies, amenities, and a seating chart |

![Events page](docs/gym-events.png)

## Highlights

- Responsive layout with a hamburger menu on small screens
- Hand-written carousel (no libraries)
- Modal ticket form with a purchase confirmation (front-end only; no real payments)
- Consistent visual system across 13 pages with Google Fonts and Font Awesome icons

## Run it

```bash
git clone https://github.com/tvisham/Gymnasium-Rental-Website.git
cd Gymnasium-Rental-Website
python -m http.server 8000
```

Open http://localhost:8000, or just open `index.html` in a browser.

## Tech

HTML5 · CSS3 · vanilla JavaScript · Google Fonts · Font Awesome

