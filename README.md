# 🏨 AURELIA GRAND — Luxury Hotel & Resort

A modern, elegant, and responsive luxury hotel and resort website built using **HTML5, Tailwind CSS, and JavaScript**.

The website provides a premium hotel experience with luxury rooms, reservation functionality, dining, spa, and resort information.

---

## ✨ Features

- 🏠 Luxury Hero Section
- 🧭 Responsive Navigation Bar
- 📅 Check-in / Check-out Booking Section
- 👥 Guest Selection
- 🛏️ Rooms & Suites Section
- 💎 Premium Luxury Design
- 📖 About / Hotel Story Section
- 🍽️ Fine Dining Information
- 🌿 Wellness / Spa Section
- 📍 Location Information
- 📱 Responsive Mobile Design
- 🔔 Reservation Modal
- ✨ Scroll-based Navbar Animation
- 🎨 Custom Gold, Black & Cream Color Theme

---

## 🛠️ Technologies Used

- HTML5
- Tailwind CSS
- JavaScript
- Bootstrap Icons
- Google Fonts
- Unsplash Images

---

## 🎨 Design

The website uses a luxury-inspired color palette:

| Color | Hex Code |
|-------|----------|
| 🖤 Black | `#0b0b0a` |
| 🖤 Dark Black | `#11100e` |
| 🟡 Gold | `#c8a96b` |
| ✨ Light Gold | `#e7cf9a` |
| 🤍 Cream | `#f4efe5` |

### Fonts

Custom fonts are used for:

- Headings
- Body Text

The typography is designed to provide a premium and elegant hotel experience.

---

## 🏨 Rooms & Suites

### Deluxe Room

An elegant sanctuary featuring premium bedding, warm textures, and refined contemporary details.

### Royal Suite

Generous living spaces, elegant furnishings, and a private lounge designed for longer stays.

### Presidential Suite

Unmatched luxury with expansive panoramic views, dedicated butler service, and custom amenities.

---

## 📋 Reservation System

Users can open the reservation modal from multiple places throughout the website.

### Reservation Form Includes

- Full Name
- Email Address
- Suite Selection
- Confirm Reservation Button

The reservation modal is controlled using JavaScript's `toggleModal()` function.

### JavaScript Example

```javascript
function toggleModal(show) {
    const modal = document.getElementById("bookingModal");

    if (show) {
        modal.classList.remove("hidden");
    } else {
        modal.classList.add("hidden");
    }
}
