
Here’s an example for each of the **110 HTML elements**, organized by their categories:

---

### **1. Document Structure**

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>My Web Page</title>
    </head>
    <body>
        <h1>Welcome to My Website</h1>
        <p>This is a simple HTML document.</p>
    </body>
</html>
```

___
### **2. Metadata and Links**

```html
<!DOCTYPE html>
<html>
    <head>
        <!-- Base URL for relative URLs -->
        <base href="https://www.example.com/">
        
        <!-- Link to external stylesheet -->
        <link rel="stylesheet" href="styles.css">
        
        <!-- Meta tag for character encoding -->
        <meta charset="UTF-8">
        
        <!-- Meta tag for viewport settings -->
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        
        <!-- Embedding internal CSS styles -->
        <style>
            body {
                font-family: Arial, sans-serif;
            }
            h1 {
                color: blue;
            }
        </style>
        
        <title>My Web Page</title>
    </head>
    <body>
        <h1>Welcome to My Website</h1>
        <p>This is a simple HTML document with embedded and linked resources.</p>
    </body>
</html>

```

___
### **3. Sectioning Elements**


```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>My Web Page</title>
        <style>
            body {
                font-family: Arial, sans-serif;
            }
            header, nav, main, section, article, aside, footer {
                margin: 20px;
                padding: 10px;
                border: 1px solid #ccc;
            }
            header {
                background-color: #f4f4f4;
            }
            footer {
                background-color: #f4f4f4;
            }
        </style>
    </head>
    <body>
        <!-- Header section with introductory content -->
        <header>
            <h1>Welcome to My Website</h1>
            <p>This is the introductory content of the page.</p>
        </header>

        <!-- Navigation links -->
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>

        <!-- Main content of the page -->
        <main>
            <!-- Section grouping content by theme -->
            <section>
                <h2>About Us</h2>
                <p>This is a section about our company.</p>
            </section>

            <!-- Article as independent content -->
            <article>
                <h2>Latest Blog Post</h2>
                <p>This is an article that represents a blog post.</p>
            </article>
        </main>

        <!-- Aside for side content (e.g., sidebar) -->
        <aside>
            <h3>Related Links</h3>
            <ul>
                <li><a href="#link1">Related Link 1</a></li>
                <li><a href="#link2">Related Link 2</a></li>
            </ul>
        </aside>

        <!-- Footer section with footer content -->
        <footer>
            <p>© 2025 My Website</p>
        </footer>

        <!-- Address section for contact information -->
        <address>
            <p>Contact us at <a href="mailto:contact@mywebsite.com">contact@mywebsite.com</a></p>
        </address>
    </body>
</html>

```

___
### **4. Text Content**


```html
	<blockquote>
	  <p>“A quote in a block.”</p>
	</blockquote>
	<cite>The Author</cite>
	<q>Inline quote</q>
	<abbr title="World Wide Web">WWW</abbr>
	<dfn>HTML</dfn>
	<time datetime="2025-01-08">January 8, 2025</time>
	<code>print("Hello, World!")</code>
	<pre>
	Preformatted text
	    preserves spaces.
	</pre>
	<var>x</var>
	<samp>Output sample</samp>
	<kbd>Ctrl+C</kbd>
	<mark>Highlighted text</mark>
	<del>Deleted text</del>
	<ins>Inserted text</ins>
	<small>Fine print</small>
	<strong>Important text</strong>
	<em>Emphasized text</em>
	<b>Bold text</b>
	<i>Italic text</i>
	<u>Underlined text</u>
	<s>Strikethrough text</s>
	<bdi>Isolated text</bdi>
	<bdo dir="rtl">Reversed text</bdo>
```

---
### **5. Grouping Content**


```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>My Web Page</title>
        <style>
            body {
                font-family: Arial, sans-serif;
            }
            .container {
                margin: 20px;
                padding: 10px;
                border: 1px solid #ccc;
                background-color: #f9f9f9;
            }
            .highlight {
                color: red;
            }
        </style>
    </head>
    <body>
        <!-- Div element as a container -->
        <div class="container">
            <h1>Welcome to My Website</h1>
            <p>This is a paragraph inside a div container.</p>

            <!-- Span element for inline content -->
            <p>Here is an <span class="highlight">important</span> word in the paragraph.</p>

            <!-- Horizontal rule for a thematic break -->
            <hr>

            <!-- Line break to separate content -->
            <p>This is the first line.<br>This is the second line after a break.</p>
        </div>
    </body>
</html>

```

___
### **6. Lists**

```html
	<ul>
	  <li>Item 1</li>
	  <li>Item 2</li>
	</ul>
	<dl>
	  <dt>Term</dt>
	  <dd>Description</dd>
	</dl>
```

---

### **7. Tables**

```html
	<table>
	  <caption>Table Title</caption>
	  <thead>
	    <tr>
	      <th scope="col">Header 1</th>
	      <th  scope="col">Header 2</th>
	    </tr>
	  </thead>
	  <tbody>
	    <tr>
	      <td scope="row">Data 1</td>
	      <td>Data 2</td>
	    </tr>
	  </tbody>
	  <tfoot>
	    <tr>
	      <td scope="row" colspan="2">Footer</td>
	    </tr>
	  </tfoot>
	</table>
	<colgroup>
	  <col span="2" style="background-color: lightgray;">
	</colgroup>
```

---

### **8. Forms**


```html
    <form action="" method="get"> <!-- You can add an attribute called novalidate it will help you during the testing that you don't need to validate the form each time -->
      <div>
        <label for="fn">First Name : </label>
        <input id="fn" type="text" name="First Name" placeholder="Add your first name" autofocus required>
      </div>
      <br>
      <div>
        <label for="ln">Last Name : </label>
        <input id="ln" type="text" name="Last Name" placeholder="Add your last name" required>
      </div>
      <br>
      <div>
        <label>User name : </label>
        <input name="UsereName" value="Gel0o" readonly type="text" />
      </div>
      <br />
      <div>
        <label>Email : </label>
        <input type="email" name="Email" placeholder="Add Email" value="gel0o.m0o@gmail.com" disabled />
      </div>

      <br />

      <div>

        <label for="pass">Password : </label>

        <input id="pass" type="password" name="Password" placeholder="Add strong password" required />
      </div>
      <br />
      <div>
        <input type="hidden" value="1234" name="id">
        <input type="color" name="color" value="#00ff00"/>
        <input type="range" name="range" min="0" max="100" step="20" value="80" />
        <input type="number" name="number" min="0" max="10" step="2" value="1"/>
      </div>
      <br>
      <div>
        <input id="win" type="radio" name="OS" value="Windows" checked />
        <label for="win">Windows</label>
      </div>
      <div>
        <input id="mac" type="radio" name="OS" value="Mac" />
        <label for="mac">Mac</label>
      </div>
      <div>
        <input id="lin" type="radio" name="OS" value="Linux" />
        <label for="lin">Linux</label>
      </div>
      <br />
      <div>
        <input id="win1" type="checkbox" name="os" value="Windows" checked>
        <label for="win1">Windows</label>
      </div>
      <div>
        <input id="mac1" type="checkbox" name="os" value="Mac">
        <label for="mac1">Mac</label>
      </div>
      <div>
        <input id="lin1" type="checkbox" name="os" value="Linux">
        <label for="lin1">Linux</label>
      </div>
      <br />
      <div>  
        <label for="con">Country :</label>
        <select id="con" name="Country"> <!-- you can use multiple attributes to select multiple options using ctrl-->
          <optgroup label="Arabian">
            <option value="Saudi Arabia">Saudi Arabia</option>
            <option value="Egypt" selected>Egypt</option>
          </optgroup>
          <optgroup label="Foreign">
            <option value="America">America</option>
            <option value="UK">UK</option>
          </optgroup>
        </select>
      </div>
        <br>
      <div>
        <label>Programming : </label>
        <input list="Prog" name="Programming language">
          <datalist id="Prog">
            <option value="Python">
            <option value="PHP">
            <option value="JavaScript">
            <option value="C#">
            <option value="C++">
          </datalist>
      </div>
        <br>
        <div>
          <label for="comment">Ask : </label>
          <textarea name="Subject" id="comment" rows="5" cols="25" placeholder="
   Add Your Comment Here"></textarea>
        </div>
        <br>
      <div>
        <label>Upload your CV :</label>
        <input type="file" name="CV">
      </div>
        <br>
      <div>
        <label>Search : </label>
        <input type="search">
      </div>
        <br>
      <div>
        <label>Add Url : </label>
        <input type="url">
      </div>
        <br>
      <div>
        <label>Date : </label>
        <input type="date">
      </div>
        <br>
      <div>
        <label>Month : </label>
        <input type="month">
      </div>
        <br>
      <div>
        <label>Time : </label>
        <input type="time">
      </div>
        <br>
      <input type="submit" value="save" />
      <input type="reset" value="reset" />
    </form>
```

---

### **9. Embedded Content**


```html
	<img src="image.jpg" alt="An image">

          
	<iframe src="https://example.com"></iframe>
	<embed src="file.pdf" type="application/pdf">
	<object data="movie.swf" type="application/x-shockwave-flash">
	  <param name="autoplay" value="true">
	</object>
	<video controls>
	  <source src="video.ogg" type="video/ogg">
	  <source src="video.mp4" type="video/mp4">
	  Your browser does not support the video element.
	</video>
	<audio controls>
	  <source src="audio.mp3" type="audio/mpeg">
	  <source src="audio.flac" type="audio/flac">
	  Your browser does not support the audio element.
	</audio>
	<track src="subtitles.vtt" kind="subtitles" srclang="en" label="English">
```

---

### **10. Interactive Elements**

```html
	<a href="https://example.com">Link</a>
	<button type="button">Click Me</button>
	 <details>
		 <!-- Question? -->
		 <summary>When did tacos first appear in the United States></summary>
		 <!-- Answer -->
          <p>Jeffrey M.Pilcher, taco historian and professor of history at the 
          University of Minnesota, says tha earliest mention of tacos in the 
          United States are in a newspaper from <time datetime="1905">1905</time>. 
          (Source: <cite><a target="_blank" href="https://www.smithsonianmag.com/arts-culture/where-did-the-taco-come-from-81228162/#:~:text=The%20first%20references%20%5Bto%20the,goes%20back%20to%20time%20immemorial.">Smithsonian Magazine</a></cite>)</p>
	</details>
	<dialog open>
	  <p>Dialog content</p>
	</dialog>
```

---

### **11. Scripting**


```html
	<script>
	  console.log("Hello, World!");
	</script>
	<noscript>
	  JavaScript is disabled in your browser.
	</noscript>
	<template>
	  <div>Template Content</div>
	</template>
	<slot></slot> <!-- Used in web components -->
```

---

### **12. Obsolete/Deprecated Elements**


```html
	<!-- These elements are not recommended for use -->
	<acronym title="Scalable Vector Graphics">SVG</acronym>
	<applet code="example.class"></applet>
	<bgsound src="sound.mp3">
	<basefont size="4">
	<big>Big text</big>
	<center>Centered text</center>
	<font size="4" color="blue">Styled text</font>
	<strike>Strikethrough text</strike>
	<tt>Teletype text</tt>
```

---

