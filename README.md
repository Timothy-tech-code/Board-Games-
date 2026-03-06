# Board Games Site

A vibrant, multi-page responsive website dedicated to the world of board games. This project showcases popular games, provides instructional content, and lists upcoming championships across Canada.

## 🎮 Live Demo

*Insert your GitHub Pages link here once deployed.*

---

## ✨ Features

* **Multi-Page Architecture**: Includes Home, Games, Play (Tutorials), Events, and Contact pages.
* **Interactive UI**:
* Custom CSS animations (tracking expand, swirl-in, and hover scaling).
* Integrated YouTube tutorials using `<iframe>`.
* Interactive Google Maps integration.


* **Event Management**: A dedicated section for Canadian chess championships with downloadable ticket functionality.
* **Fully Responsive**: Optimized for Mobile, Tablet, and Desktop using CSS Media Queries.
* **AOS Integration**: Smooth "Animate On Scroll" effects for a modern feel.

## 📂 Project Structure

```text
├── index.html          # Main landing page & popular games overview
├── games.html          # Catalog of favorite games with pricing
├── how-to-play.html    # Video tutorial section
├── events.html         # Championship schedule & ticket downloads
├── contacts.html       # Social links and location map
├── style.css           # Custom styles, animations, and media queries
└── Tickets/            # Folder containing ticket assets (PNGs)

```

## 🚀 Technical Highlights

### 🎨 Styling & Animations

The site uses a mix of Google Fonts (Sarpanch, Red Rose, Oswald, etc.) to give each section a unique personality. Animations are handled via keyframes:

* `swirl-in-fwd`: Used for the logo entry.
* `tracking-in-expand`: Used for page headers.
* `scale-up-center`: Used for interactive navigation hover states.

### 📱 Responsive Breakpoints

The `style.css` file includes specific configurations for:

* **Mobile (< 425px)**: Stacked layouts and adjusted font sizes.
* **Tablet (426px - 1024px)**: Grid adjustments for game lists and containers.

### 🛠️ External Libraries

* [AOS (Animate On Scroll)](https://michalsnik.github.io/aos/): Used for scroll-triggered entrance animations.

## 💻 How to Run Locally

1. **Clone the repository**:
```bash
git clone https://github.com/your-username/board-games-site.git

```


2. **Navigate to the directory**:
```bash
cd board-games-site

```


3. **Open the project**:
Simply double-click `index.html` to view it in your browser.

---

## 👤 Author

**Timothy** - *Web Development & Design*

---

### Future Improvements

* [ ] Add a functional backend for the Log-In form.
* [ ] Implement a shopping cart for the "Order" buttons.
* [ ] Expand the events list to include other provinces.
