Semantic HTML5 elements provide meaningful structure to web pages, making it easier for developers and browsers to understand the content. Here’s a list of key semantic HTML5 elements with examples:

---

### 1. **`<header>`**

Represents introductory content or a group of introductory content for a section or page.

```html
	<header>
	  <h1>My Blog</h1>
	  <nav>
	    <ul>
	      <li><a href="#home">Home</a></li>
	      <li><a href="#about">About</a></li>
	      <li><a href="#contact">Contact</a></li>
	    </ul>
	  </nav>
	</header>
```

---
### 2. **`<nav>`**

Defines navigation links for the website or a section.

```html
	<nav>
	  <ul>
	    <li><a href="#home">Home</a></li>
	    <li><a href="#services">Services</a></li>
	    <li><a href="#contact">Contact</a></li>
	  </ul>
	</nav>
```

---

### 3. **`<main>`**

Represents the main content of the document, unique and central to the page.

```html
	<main>
	  <h2>Welcome to My Blog</h2>
	  <p>This is where the main content of the page resides.</p>
	</main>
```

---

### 4. **`<section>`**

Defines a thematic grouping of content.

```html
	<section>
	  <h2>About Us</h2>
	  <p>We are a team of passionate developers.</p>
	</section>
```

---

### 5. **`<article>`**

Represents self-contained content, such as a blog post or news article.

```html
	<article>
	  <h2>How to Learn HTML</h2>
	  <p>HTML is the foundation of web development.</p>
	</article>
```

---

### 6. **`<aside>`**

Contains content related to the main content, such as sidebars or ads.

```html
	<aside>
	  <h3>Related Articles</h3>
	  <ul>
	    <li><a href="#article1">HTML Tips</a></li>
	    <li><a href="#article2">CSS Basics</a></li>
	  </ul>
	</aside>
```

---

### 7. **`<footer>`**

Defines footer content for a section or page.

```html
	<footer>
	  <p>&copy; 2025 My Website. All rights reserved.</p>
	</footer>
```

---

### 8. **`<figure>`**

Used to group media elements like images and captions.

```html
	<figure>
	  <img src="image.jpg" alt="A beautiful view">
	  <figcaption>A breathtaking view of nature.</figcaption>
	</figure>
```

---

### 9. **`<figcaption>`**

Provides a caption for the `<figure>` element.

```html
	<figure>
	  <img src="sunrise.jpg" alt="Sunrise">
	  <figcaption>Sunrise over the mountains.</figcaption>
	</figure>
```

---

### 10. **`<mark>`**

Highlights text.

```html
<p>Don't forget to <mark>review your code</mark> before submitting it.</p>
```

---

### 11. **`<time>`**

Represents a specific time or duration.

```html
<p>The event starts at <time datetime="2025-01-15T09:00">9:00 AM on January 15, 2025</time>.</p>
```

---

### 12. **`<details>`**

Creates a collapsible content section.

```html
<details>
  <summary>More Info</summary>
  <p>Here is some additional information.</p>
</details>
```

---

### 13. **`<summary>`**

Provides a summary for the `<details>` element.

```html
<details>
  <summary>Click for Details</summary>
  <p>This is the detailed content.</p>
</details>
```

---

### 14. **`<address>`**

Provides contact information.

```html
<address>
  Contact us at: <a href="mailto:info@example.com">info@example.com</a>
</address>
```

---

### 15. **`<code>`**

Defines inline code snippets.

```html
<p>Use <code>console.log('Hello, world!');</code> to debug JavaScript.</p>
```

---

### 16. **`<blockquote>`**

Denotes a section of quoted text.

```html
<blockquote>
  "The journey of a thousand miles begins with one step."
</blockquote>
```

---

### 17. **`<cite>`**

References the title of a work.

```html
<cite>The Great Gatsby</cite> by F. Scott Fitzgerald.
```

---

### 18. **`<em>`**

Emphasizes text (typically italicized).

```html
<p><em>Important note:</em> Always validate user input.</p>
```

---

### 19. **`<strong>`**

Indicates strong importance (typically bolded).

```html
<p><strong>Warning:</strong> Do not share your password.</p>
```

---

### 20. **`<dl>`, `<dt>`, `<dd>`**

Used for definition lists.

```html
	<dl>
	  <dt>HTML</dt>
	  <dd>Hypertext Markup Language</dd>
	  <dt>CSS</dt>
	  <dd>Cascading Style Sheets</dd>
	</dl>
```

---

### 21. **`<table>`, `<thead>`, `<tbody>`, `<tfoot>`**

Semantic table structure.

```html
	<table>
	  <thead>
	    <tr>
	      <th scope="col">Product</th>
	      <th scope="col">Price</th>
	    </tr>
	  </thead>
	  <tbody>
	    <tr>
	      <td scope="row">Apple</td>
	      <td>$1</td>
	    </tr>
	    <tr>
	      <td scope="row">Banana</td>
	      <td>$0.5</td>
	    </tr>
	  </tbody>
	  <tfoot>
	    <tr>
	      <td>Total</td>
	      <td>$1.5</td>
	    </tr>
	  </tfoot>
	</table>
```

---

Using these elements helps structure content meaningfully, improving accessibility and SEO for your web pages.