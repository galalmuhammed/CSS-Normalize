## 🔹 **Display Types – Block, Inline, and Inline-Block**
---


📌 **Block Elements**

- Take full width if no width is set.
- Add a line break (appear on a new line).
- Respect `padding`, `margin`, `width`, and `height`.

📌 **Inline Elements**

- Ignore `width` and `height` (size fits the content).
- Don't add a line break (elements are displayed next to each other).
- Respect `padding` and `margin` (only left and right).

📌 **Inline-Block Elements**

- Behave like `inline` (fit-content width).
- Don't add a line break (elements appear next to each other).
- Respect `padding`, `margin`, `width`, and `height`.

---

🔹 **Comparison Table**

|Property|Block|Inline|Inline-Block|
|---|---|---|---|
|Takes Full Width|✅|❌|❌|
|Respects Width & Height|✅|❌|✅|
|Adds Line Break|✅|❌|❌|
|Elements Side by Side|❌|✅|✅|
|Respects Padding & Margin|✅|Partial (Left/Right)|✅|

---

## 🔹 **Additional Notes**

📌 **Hiding Elements:**

- `display: none;` → Hides the element and removes it from the document flow.
- `visibility: hidden;` → Hides the element but keeps its space in the layout.

---

## 🔹 **Other Display Properties**

- **float**
- **flex**
- **grid**

