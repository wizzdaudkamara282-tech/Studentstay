# StudentStay

**A Web-Based Student Accommodation Finder for Freetown, Sierra Leone**

A responsive 5-page website for students looking for accommodation in Freetown.

---

## 1. Background
Students in Freetown usually look for accommodation through WhatsApp groups, Facebook posts, agents and friends. The information is scattered, and it is hard to find accurate, up-to-date rooms. Many students use mobile phones with limited data, so the site must be mobile-friendly, simple and lightweight.

## 2. Problem
- Hard to find rooms that match a budget and are close to campus
- Accommodation information is scattered across social media and agents
- Fake listings, unclear prices and hidden fees
- No single place to compare price, location, distance and facilities
- No organised platform for owners to reach students

## 3. Solution
StudentStay lets students search by location and price, compare rooms, view key details and contact the owner or manager directly.

## 4. Target Users
- **Students (primary):** about 17 to 30 years old, including first-year students new to Freetown
- **Parents and guardians (secondary):** help students choose and pay for rooms
- **Property owners and managers (tertiary):** advertise rooms to students

**Personas:** Amara Kamara (19, first-year IT student from Bo) and Fatmata Sesay (22, second-year student looking for a cheaper room with bills included).

## 5. Pages
| Page | File | Content |
|---|---|---|
| Home | `index.html` | Hero heading "Find Your Perfect Accommodation", search (Location, Price), Featured Listings |
| About | `about.html` | Project information, three values (Safe, Affordable, Convenient), banner |
| Services | `services.html` | Four service cards: Verified Listings, Affordable Prices, Easy Contact, Student Support |
| Listings | `listings.html` | Major feature: filters and room cards with photo, area, distance, facilities, monthly price and VIEW DETAILS |
| Contact | `contact.html` | Location, phone, email, working hours and a message form |

### 5.1 Home (`index.html`)
Hero heading "Find Your Perfect Accommodation", search by Location and Price, and Featured Listings.

<p align="center">
  <img src="images/screenshots/home.png" alt="StudentStay Home page" width="100%">
</p>

### 5.2 About (`about.html`)
Project information, three values (Safe, Affordable, Convenient) and a banner.

<p align="center">
  <img src="images/screenshots/about.png" alt="StudentStay About page" width="100%">
</p>

### 5.3 Services (`services.html`)
Four service cards: Verified Listings, Affordable Prices, Easy Contact and Student Support.

<p align="center">
  <img src="images/screenshots/services.png" alt="StudentStay Services page" width="100%">
</p>

### 5.4 Listings (`listings.html`)
The major feature: filters and room cards with photo, area, distance, facilities, monthly price and VIEW DETAILS.

<p align="center">
  <img src="images/screenshots/listings.png" alt="StudentStay Listings page" width="100%">
</p>

### 5.5 Contact (`contact.html`)
Location, phone, email, working hours and a message form.

<p align="center">
  <img src="images/screenshots/contact.png" alt="StudentStay Contact page" width="100%">
</p>

---

## 6. Navigation and User Journey
- Header menu on every page: Logo, Home, About, Services, Listings, Contact
- Navigation links stacked in a list on mobile
- Footer on every page: logo, page links and copyright
- Clicking the logo returns to Home
- User journey: **Need → Search → Compare → Decide → Contact**

## 7. Features
- Responsive layout for mobile, tablet and desktop (breakpoints at 768px and 1024px)
- Mobile-first CSS
- Room listings with photos
- Contact page with message form
- Semantic HTML and accessible navigation (alt text, labels)

## 8. Design
- Neutral palette: white background (`#FFFFFF`), grey surfaces (`#D9D9D9`), black footer and buttons (`#000000`)
- Font: Inter (Google Fonts), chosen for readability on small screens
- Same header and footer on every page for consistency
- Based on the Assignment 1 wireframes

## 9. Technologies
HTML5, CSS3 (mobile-first, pure CSS menu), Google Fonts, Git and GitHub

## 10. Project Structure
```
studentstay/
├── index.html
├── about.html
├── services.html
├── listings.html
├── contact.html
├── css/style.css
├── images/
│   └── screenshots/
└── README.md
```

## 11. Run Locally
Open `index.html` in a browser. No installation is needed.

## 12. Image Credits
Room photos are used for educational purposes only.
