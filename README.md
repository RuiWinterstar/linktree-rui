# 📚 Rui's Shelf

> A personal link page for **Rui N.A Winterstar**, collecting social media and online platforms in one place.

**Rui's Shelf** is a simple personal link page inspired by the idea of a small digital shelf, where visitors can find Rui's social media accounts and other online spaces in one place.

The page is designed with a warm, vintage-inspired visual style using custom artwork, decorative borders, and a bookish aesthetic.

## ✦ Features

* 📱 Responsive layout for different screen sizes
* 🖼️ Custom profile picture and decorative assets
* 🔗 Social media links
* 🎨 Custom background and decorative borders
* ✨ Hover animation on social media buttons
* 🔤 Custom typography using Google Fonts
* 🌐 Fully static webpage with no backend required

## 🛠️ Built With

* **HTML5** — page structure
* **CSS3** — styling, layout, and animations
* **Google Fonts** — custom typography
* **PNG assets** — profile picture, social media buttons, borders, background, and favicon

## 📁 Project Structure

```text
linktree-rui/
│
├── assets/
│   ├── WAch.png
│   ├── background.png
│   ├── favicon.png
│   ├── fb.png
│   ├── ig.png
│   ├── lowerborder.png
│   ├── profilepic.png
│   ├── tt.png
│   ├── upperborder.png
│   ├── xtwt.png
│   └── yt.png
│
├── index.html
├── style.css
└── README.md
```

## 🚀 Running Locally

No build tools or dependencies are required.

1. Clone this repository:

```bash
git clone https://github.com/RuiWinterstar/linktree-rui.git
```

2. Open the project folder:

```bash
cd linktree-rui
```

3. Open `index.html` in your browser.

That's it. Humanity has somehow managed to make a website that doesn't require installing 700 MB of dependencies.

## ✏️ Customization

### Changing the profile

Replace:

```text
assets/profilepic.png
```

with your own profile image while keeping the same filename, or update the image path inside `index.html`.

### Changing social media links

The social media buttons are defined directly in `index.html`.

For example:

```html
<a href="YOUR-LINK-HERE" class="btn">
  <img src="assets/ig.png" alt="Instagram">
</a>
```

Replace `YOUR-LINK-HERE` with the desired URL.

### Changing the background

The webpage background is controlled in `style.css`:

```css
.container {
  background: url('assets/background.png') center/cover no-repeat;
}
```

Replace `assets/background.png` with another image or change the CSS background settings.

### Changing the glow effect

The glow settings can be adjusted from the variables at the top of `style.css`:

```css
:root {
  --glow-color: #d4a574;
  --glow-size: 10px;
  --glow-intensity: 0.6;
}
```

## 📱 Social Links

The page currently contains links to:

* WhatsApp Channel
* Facebook
* YouTube
* TikTok
* X / Twitter
* Instagram

## 🎨 Design

The visual concept combines:

* warm brown tones
* vintage decorative elements
* handwritten-style typography
* custom illustrated assets
* bookshelf / personal archive inspiration

The goal is to make a simple link page feel more personal than a standard link aggregator.

## 📌 Notes

This project is intentionally kept simple and uses only static HTML and CSS. There is currently no JavaScript, database, API, or server-side functionality.

## 👤 Author

**Rui N.A Winterstar**

GitHub: [@RuiWinterstar](https://github.com/RuiWinterstar)

---

Made with HTML, CSS, custom assets, and an unreasonable amount of time spent making six social media buttons look pretty.
