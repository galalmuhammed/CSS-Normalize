
### **Global Attributes in HTML**

**Global attributes** are attributes that can be used on almost any HTML element. They are versatile and provide additional control over the behavior, appearance, or interaction of HTML elements.

|     Attribute     |              Function              |
|:-----------------:|:----------------------------------:|
|    `accesskey`    | Keyboard shortcut for the element. |
| `autocapitalize`  |    Text capitalization control.    |
|      `class`      |  Styling and scripting purposes.   |
| `contenteditable` |        Editable text areas.        |
|     `data-*`      |      Custom data attributes.       |
|       `dir`       |          Text direction.           |
|    `draggable`    |       Drag-and-drop support.       |
|     `hidden`      |         Hides an element.          |
|       `id`        |         Unique identifier.         |
|      `inert`      | Makes an element non-interactive.  |
|    `inputmode`    |     Keyboard type for inputs.      |
|       `is`        |   Custom element identification.   |
|      `lang`       |        Language of content.        |
|      `part`       |   Styling parts of a shadow DOM.   |
|      `role`       |  Semantic role for accessibility.  |
|      `slot`       |   Slot name for Web Components.    |
|   `spellcheck`    |    Checks spelling and grammar.    |
|      `style`      |          Inline styling.           |
|    `tabindex`     |             Tab order.             |
|      `title`      |           Tooltip text.            |
|    `translate`    |       Translation settings.        |


---

### 1. **`accesskey`**

- **Description**: Specifies a shortcut key to activate/focus an element.
- **Example**:
  ```html
  <button accesskey="s">Press Alt+S to submit</button>
  ```

---

### 2. **`autocapitalize`**

- **Description**: Controls text capitalization inside an element.
- **Values**:
  - `none`: No capitalization.
  - `sentences`: Capitalize the first letter of each sentence.
  - `words`: Capitalize the first letter of each word.
  - `characters`: Capitalize all characters.
- **Example**:
  ```html
  <input type="text" autocapitalize="words" />
  ```

---

### 3. **`class`**

- **Description**: Assigns one or more class names to an element for styling or scripting.
- **Example**:
  ```html
  <div class="container highlight"></div>
  ```

---

### 4. **`contenteditable`**

- **Description**: Makes an element editable by the user.
- **Values**:
  - `true`: Editable.
  - `false`: Not editable.
- **Example**:
  ```html
  <div contenteditable="true">You can edit this text!</div>
  ```

---

### 5. **`data-*`**

- **Description**: Stores custom data attributes for scripting.
- **Example**:
  ```html
  <div data-id="123" data-role="admin"></div>
  ```

---

### 6. **`dir`**

- **Description**: Specifies text direction.
- **Values**:
  - `ltr`: Left-to-right (default).
  - `rtl`: Right-to-left.
  - `auto`: Based on content.
- **Example**:
  ```html
  <p dir="rtl">This text is right-to-left.</p>
  ```

---

### 7. **`draggable`**

- **Description**: Specifies if an element is draggable.
- **Values**:
  - `true`: Draggable.
  - `false`: Not draggable.
- **Example**:
  ```html
  <img src="image.jpg" draggable="true" />
  ```

---

### 8. **`hidden`**

- **Description**: Hides an element (it’s still in the DOM but not visible).
- **Example**:
  ```html
  <p hidden>This paragraph is hidden.</p>
  ```

---

### 9. **`id`**

- **Description**: Assigns a unique identifier to an element.
- **Example**:
  ```html
  <h1 id="main-title">Hello, World!</h1>
  ```


---

### 10. **`inert`**

- **Description**: Makes an element non-interactive (not focusable or clickable).
- **Example**:
  ```html
  <div inert>This section is not interactive.</div>
  ```

---

### 11. **`inputmode`**

- **Description**: Specifies the type of virtual keyboard to display.
- **Values**:
  - `text`, `decimal`, `numeric`, `tel`, `email`, `url`.
- **Example**:
  ```html
  <input type="text" inputmode="numeric" />
  ```

---

### 12. **`is`**

- **Description**: Used with custom elements (Web Components).
- **Example**:
  ```html
  <button is="custom-button">Click me</button>
  ```

---

### 13. **`lang`**

- **Description**: Specifies the language of an element's content.
- **Example**:
  ```html
  <p lang="en">Hello, World!</p>
  ```

---

### 14. **`part`**

- **Description**: Used to define parts of a shadow DOM for styling.
- **Example**:
  ```html
  <div part="header">Header</div>
  ```

---

### 15. **`role`**

- **Description**: Defines the semantic role for accessibility.
- **Example**:
  ```html
  <div role="navigation"></div>
  ```

---

### 16. **`slot`**

- **Description**: Assigns a slot name for Web Components.
- **Example**:
  ```html
  <slot name="title"></slot>
  ```

---

### 17. **`spellcheck`**

- **Description**: Specifies whether to check spelling/grammar.
- **Values**:
  - `true`: Check spelling.
  - `false`: Don’t check spelling.
- **Example**:
  ```html
  <textarea spellcheck="true"></textarea>
  ```

---

### 18. **`style`**

- **Description**: Adds inline CSS styles.
- **Example**:
  ```html
  <p style="color: red;">This is red text.</p>
  ```

---

### 19. **`tabindex`**

- **Description**: Sets the tab order of an element.
- **Example**:
  ```html
  <button tabindex="1">First</button> <button tabindex="2">Second</button>
  ```

---

### 20. **`title`**

- **Description**: Adds a tooltip when hovering over an element.
- **Example**:
  ```html
  <button title="Click to submit">Submit</button>
  ```

---

### 21. **`translate`**

- **Description**: Specifies whether the content should be translated.
- **Values**:
  - `yes`: Translatable.
  - `no`: Not translatable.
- **Example**:
  ```html
  <p translate="no">BrandName</p>
  ```

---

These global attributes can be combined with almost any HTML element to enhance its functionality or improve user experience!
