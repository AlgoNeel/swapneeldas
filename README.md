# Modern Personal Portfolio - Swapneel Das

A sleek, responsive, and high-performance personal portfolio website built with **Tailwind CSS** and **Vanilla JavaScript**. This project showcases my academic journey as an English Literature student, my professional skill set, and my digital presence.

## 🚀 Features

* **Dynamic Hero Section**: Features a typewriter effect and a modern, high-contrast UI.
* **Deep-Linking for Socials**: Custom JavaScript logic that attempts to open Facebook, Instagram, and X (Twitter) directly in their respective mobile apps, with a web fallback.
* **Smooth Scroll & Reveal**: Integrated "Scroll Reveal" animations for an interactive user experience.
* **Responsive Design**: Fully optimized for mobile, tablet, and desktop screens.
* **Academic Timeline**: A stylized vertical timeline highlighting educational milestones from primary school to ongoing university studies.
* **Glassmorphism UI**: Uses backdrop filters and subtle gradients for a modern "glass" aesthetic.

## 🛠️ Built With

* **HTML5 & CSS3**: Semantic structure and custom styling.
* **Tailwind CSS**: For utility-first rapid styling and layout.
* **JavaScript (ES6+)**: Custom logic for animations, mobile menus, and deep-linking.
* **Google Fonts**: 'Inter' and 'Outfit' for a premium typography feel.

## 📁 Project Structure

```text
├── index.html          # Main portfolio file
├── img/                
│   └── photo1.png      # Profile picture (About section)
└── README.md           # Project documentation

```

## 💻 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git

```

### 2. Add your Photo

Make sure you have a folder named `img` and place your profile picture inside it. Name the file `photo1.png` or update the `src` attribute in the "About" section of `index.html`.

### 3. Open the Project

Simply open `index.html` in any modern web browser to view the site. No local server or build process is required!

## 📱 Mobile App Linking

The "Contact" section includes a specialized `openSocial` function.

* **On Mobile**: It tries to launch apps using URI schemes (`fb://`, `instagram://`, etc.).
* **On Desktop**: It opens the links in a new browser tab with `target="_blank"`.

## 📄 License

This project is for personal use. Feel free to use the code as a template for your own portfolio.

## 🤝 Contact

Swapneel Das

Email: [swapneeldas.extra@gmail.com](mailto:swapneeldas.extra@gmail.com)

Facebook: [swapneeldasfx](https://www.facebook.com/swapneeldasfx)
