# Chapter 2: HTML

HTML (**HyperText Markup Language**) is the **structure** of every webpage.  
It tells the browser *what* the content is (headings, paragraphs, lists, images), not how it looks — that’s CSS.

---

## 🛠 Boilerplate (Every Page Needs This)

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>My Site</title>
</head>
<body>
  <h1>Hello World</h1>
  <p>This is a paragraph.</p>
</body>
</html>
````

* `<!DOCTYPE html>` → tells the browser this is HTML5
* `<head>` → meta info (title, charset, links to CSS)
* `<body>` → everything that shows up on the page

👉 Rule: exactly **one `<h1>`** per page.

---

## 🔑 Core Elements

### Headings

```html
<h1>Main Title</h1>
<h2>Subsection</h2>
<h3>Smaller Section</h3>
```

* Use `<h1>` for the main page title.
* `<h2>–<h6>` for subheadings (in order).

---

### Paragraphs

```html
<p>This is a block of text.</p>
```

---

### Links

```html
<a href="https://example.com">Go to Example</a>
<a href="#about">Jump to About section</a>
<a href="mailto:you@example.com">Email Me</a>
```

---

### Images

```html
<img src="me.jpg" alt="Portrait of me smiling">
```

* Always use `alt` text for accessibility.

---

### Lists

```html
<ul>
  <li>Learn Git</li>
  <li>Build a website</li>
  <li>Deploy to GitHub Pages</li>
</ul>
```

* `<ul>` → unordered (bullets)
* `<ol>` → ordered (numbers)

---

### Structural Elements

```html
<header>Site title + nav</header>
<main>Main content</main>
<section id="about">About me</section>
<footer>© 2025 My Name</footer>
```

👉 Prefer semantic tags instead of `<div>` everywhere.

---

## 🌐 Internal Anchors

Link to sections in the same page:

```html
<nav>
  <a href="#home">Home</a>
  <a href="#projects">Projects</a>
</nav>

<section id="home">
  <h1>Welcome</h1>
</section>
<section id="projects">
  <h2>My Projects</h2>
</section>
```

---

## 📦 Attributes

* `id` → unique identifier for anchors or CSS
* `class` → reusable styling hook
* `src` → file location for images or embeds
* `alt` → description for images
* `href` → link destination

Example:

```html
<p id="intro" class="highlight">Welcome to my page!</p>
```

---

## ⚡ Best Practices

* One `<h1>` per page
* Logical heading order (`h2` under `h1`, never jump straight to `h4`)
* Use semantic tags (`header`, `footer`, `main`)
* Write meaningful `alt` text (“Dog playing fetch”, not “image.jpg”)
* Links should describe destination (“See Projects” not “Click here”)

---

