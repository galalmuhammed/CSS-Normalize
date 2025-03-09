
---

# CSS Pseudo-Elements: The Ultimate Guide

Pseudo-elements **style specific parts of an element** (e.g., the first letter, lines, or inserting content).

📌 **Note:** `::before` and `::after` are often used for **drawing elements** or **adding empty content** using `content: '';`.

---

## [ 1 ] Common Pseudo-Elements

|Pseudo-Element|Description|Example Usage|
|---|---|---|
|**`::before`**|Inserts content **before** an element.|`css button::before { content: "🔥"; }`|
|**`::after`**|Inserts content **after** an element.|`css button::after { content: " (Click me!)"; color: gray; }`|
|**`::first-letter`**|Styles the **first letter** of a text block.|`css p::first-letter { font-size: 2em; font-weight: bold; color: red; }`|
|**`::first-line`**|Styles the **first line** of a paragraph.|`css p::first-line { font-weight: bold; color: blue; }`|
|**`::selection`**|Styles text when **highlighted**.|`css ::selection { background: yellow; color: black; }`|
|**`::placeholder`**|Styles **input placeholders**.|`css input::placeholder { color: gray; font-style: italic; }`|
|**`::marker`**|Styles list bullets or numbers.|`css li::marker { color: red; font-size: 1.2em; }`|
|**`::backdrop`**|Styles the background of **modals** (`<dialog>` elements).|`css ::backdrop { background: rgba(0, 0, 0, 0.5); }`|

---

## [ 2 ] `::before` → Inserts Content Before an Element

|Feature|Description|
|---|---|
|**Behavior**|Inserts **content** before the element.|
|**Common Uses**|Icons, decorative text, tooltips.|
|**Example**|`css button::before { content: "🔥"; }`|
|**Effect**|Adds a **fire emoji** before the button text.|

---

## [ 3 ] `::after` → Inserts Content After an Element

|Feature|Description|
|---|---|
|**Behavior**|Inserts **content** after the element.|
|**Common Uses**|Tooltips, additional styling.|
|**Example**|`css button::after { content: " (Click me!)"; color: gray; }`|
|**Effect**|Adds **hint text** after the button.|

---

## [ 4 ] `::first-letter` → Styles the First Letter

|Feature|Description|
|---|---|
|**Behavior**|Styles the **first letter** of a text block.|
|**Common Uses**|Drop caps, styling headers.|
|**Example**|`css p::first-letter { font-size: 2em; font-weight: bold; color: red; }`|
|**Effect**|First letter is **bigger and red**.|

---

## [ 5 ] `::first-line` → Styles the First Line

|Feature|Description|
|---|---|
|**Behavior**|Styles the **first line** of a paragraph.|
|**Common Uses**|Emphasizing first lines in articles.|
|**Example**|`css p::first-line { font-weight: bold; color: blue; }`|
|**Effect**|First line is **bold and blue**.|

---

## [ 6 ] `::selection` → Styles Text When Highlighted

|Feature|Description|
|---|---|
|**Behavior**|Changes the **appearance of selected text**.|
|**Common Uses**|Custom selection colors.|
|**Example**|`css ::selection { background: yellow; color: black; }`|
|**Effect**|Selected text is **yellow with black text**.|

---

## [ 7 ] `::placeholder` → Styles Input Placeholders

|Feature|Description|
|---|---|
|**Behavior**|Styles the **placeholder text** inside inputs.|
|**Common Uses**|Customizing form placeholders.|
|**Example**|`css input::placeholder { color: gray; font-style: italic; }`|
|**Effect**|Placeholder text is **gray and italic**.|

---

## [ 8 ] `::marker` → Styles List Markers (Bullets, Numbers)

|Feature|Description|
|---|---|
|**Behavior**|Styles **bullets and numbers** in lists.|
|**Common Uses**|Customizing list markers.|
|**Example**|`css li::marker { color: red; font-size: 1.2em; }`|
|**Effect**|Bullets/numbers turn **red and larger**.|

---

## [ 9 ] `::backdrop` → Styles Modal Backgrounds

|Feature|Description|
|---|---|
|**Behavior**|Styles the **background of modals**.|
|**Common Uses**|Dimming background in dialogs.|
|**Example**|`css ::backdrop { background: rgba(0, 0, 0, 0.5); }`|
|**Effect**|Background turns **dark when a modal is open**.|

---

## [ 10 ] Additional Pseudo-Elements

|Pseudo-Element|Description|Example Usage|
|---|---|---|
|**`::file-selector-button`**|Styles the button inside `<input type="file">`.|`css input::file-selector-button { background: blue; color: white; }`|
|**`::spelling-error`**|Styles words flagged as spelling errors (browser support limited).|`css ::spelling-error { background: red; }`|
|**`::grammar-error`**|Styles words flagged as grammar errors.|`css ::grammar-error { text-decoration: underline wavy blue; }`|
|**`::cue`**|Styles subtitles and captions in media.|`css ::cue { color: yellow; font-size: 18px; }`|
|**`::part()`**|Styles elements inside Web Components.|`css ::part(button) { background: green; }`|

---

## [ 11 ] Quick Tip

|Tip|Description|
|---|---|
|**Live Testing in Chrome**|Right-click an element → Select **Inspect** → Enable **:hover, :focus, or other states** under the Styles panel.|

---

## [ 12 ] Final Thoughts

|Concept|Key Takeaways|
|---|---|
|**`::before` & `::after`**|Insert **extra content** before or after an element.|
|**`::first-letter` & `::first-line`**|Style specific parts of **text content**.|
|**`::selection`**|Change **highlighted text appearance**.|
|**`::placeholder`**|Customize **form placeholders**.|
|**`::marker`**|Style **list bullets/numbers**.|
|**`::backdrop`**|Customize **modal backgrounds**.|
|**Additional Pseudo-Elements**|Target file upload buttons, grammar errors, captions, and more.|
