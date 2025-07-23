# Wedding RSVP Website

A simple and elegant RSVP website built using **HTML**, **CSS**, and **JavaScript** for managing wedding guest confirmations.  
Guests can enter their unique RSVP code to confirm attendance and list their reserved seats.

---

## Features
- **Unique RSVP Codes** – Guests enter a code to access their allocated seats.
- **Dynamic Guest Input Fields** – The number of guest name fields depends on their reserved seat allocation.
- **Simple Front-End Only** – Runs in any modern browser with no installation required.
- **Customizable Design** – Easily update wedding colors, background, and theme.

---

## How to Use
1. Open `index.html` in your browser to test locally.
2. Update the `inviteList` inside the script to add RSVP codes and seat counts:
   ```js
   const inviteList = {
     "FAM123": 4,
     "COUPLE7": 2,
     "SOLO9": 1
   };
