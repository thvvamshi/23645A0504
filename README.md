# AffordMed URL Shortener

A simple, fast, and lightweight **URL Shortener** built with **React + Vite + TailwindCSS**.  
This project allows users to shorten long URLs, manage them locally, and quickly copy/share shortened links.

---

## 🚀 Features
- Shorten up to **5 URLs at a time**.
- **Validate URLs** before shortening.
- Generate unique short codes using **nanoid**.
- Save shortened URLs in **localStorage** so they persist after refresh.
- **Copy short links** with one click.
- **Delete links** when no longer needed.
- Responsive, clean, and simple UI built with **TailwindCSS**.
- Uses **React Router** for navigation (Home & About pages).

---

## 🛠️ Tech Stack
- **Frontend**: React + Vite  
- **Styling**: TailwindCSS  
- **Routing**: React Router DOM  
- **ID Generation**: nanoid  
- **Storage**: Browser LocalStorage  

---

## 📂 Project Structure
affordmed-url-shortener/
├── public/ # Static assets
├── src/
│ ├── components/ # Reusable UI components
│ │ ├── Navbar.jsx
│ │ └── UrlCard.jsx
│ ├── pages/ # Main pages
│ │ ├── Home.jsx
│ │ └── About.jsx
│ ├── App.jsx # Main app structure
│ ├── main.jsx # Entry point
│ └── index.css # Tailwind styles
├── package.json
├── tailwind.config.js
└── vite.config.js




---

## ⚙️ Installation & Setup

1. **Clone the repo**
   ```bash
   git clone https://github.com/thvvamshi/23645a0504.git
npm install
npm run dev
http://localhost:5173


🎯 How It Works

Enter a valid long URL (e.g., https://example.com).

The app validates the format.

A unique short code (e.g., aff.ly/abc123) is generated using nanoid.

The mapping { shortCode → longURL } is saved in localStorage.

Users can:

Copy the short URL

Open the original link

Delete the entry

Since it’s frontend-only, links are stored per browser/device.

<img width="1895" height="850" alt="Screenshot 2025-08-26 135507" src="https://github.com/user-attachments/assets/f7886744-378b-4114-a6fc-0ca85fb8a3b5" />

<img width="1873" height="802" alt="Screenshot 2025-08-26 135612" src="https://github.com/user-attachments/assets/9bcc2cf9-e979-421b-96dd-6445e763a61c" />


<img width="1860" height="789" alt="image" src="https://github.com/user-attachments/assets/f4d12407-1fc8-458b-b040-1b81a502cc2f" />

## **System Design**

You can read the detailed system design document here:  
👉 [AffordMed Professional System Design (PDF)](./AffordMed_Professional_System_Design.pdf)


