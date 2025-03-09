
---

### 🔹 Font Properties – Defining Text Appearance

|Property|Description|Values & Examples|
|---|---|---|
|**font-family**|Specifies the font used for text. It's recommended to include fallback fonts.|`"Arial", sans-serif`|
|**font-size**|Defines text size using absolute (`px`, `pt`) or relative (`em`, `%`, `rem`) units.|`18px`, `1.2em`, `100%`|
|**font-weight**|Controls text thickness.|`normal`, `bold`, `400`, `700`|
|**font-style**|Defines text appearance.|`normal`, `italic`, `oblique`|

### **Best for:**

✔ Creating readable and visually appealing text styles.

### **Example:**

```css
.text-example {
    font-family: "Arial", sans-serif; /* Uses Arial with a sans-serif fallback */
    font-size: 18px;
    font-weight: bold;
    font-style: italic;
}
```

---

### 🔹 Text Properties – Structuring Text Layout

|Property|Description|Values & Examples|
|---|---|---|
|**text-align**|Aligns text horizontally within an element.|`left`, `right`, `center`, `justify`|
|**text-indent**|Adds indentation to the first line.|`20px`, `2em`|
|**line-height**|Controls space between lines, improving readability.|`1.5`, `120%`|
|**letter-spacing**|Adjusts space between characters.|`normal`, `2px`, `0.1em`|
|**word-spacing**|Modifies space between words.|`normal`, `5px`, `0.5em`|
|**text-transform**|Changes text case.|`uppercase`, `lowercase`, `capitalize`|
|**text-decoration**|Adds styles to text.|`none`, `underline`, `overline`, `line-through`|
|**text-shadow**|Applies shadow effects.|`2px 2px 5px gray`|

### **Best for:**

✔ Controlling text positioning and spacing for better readability.

### **Example:**

```css
.heading {
    text-align: center; /* Centers the text */
    line-height: 1.5; /* Enhances readability */
    letter-spacing: 2px;
    text-transform: uppercase;
    text-shadow: 2px 2px 5px gray;
}
```

---

### 🔹 Overflow and Clipping – Handling Long Text

|Property|Description|Values & Examples|
|---|---|---|
|**overflow**|Determines how content behaves when it exceeds its container.|`visible`, `hidden`, `scroll`, `auto`|
|**text-overflow**|Works with `overflow: hidden;` to display an ellipsis (`...`) when text is clipped.|`ellipsis`, `clip`|
|**white-space**|Controls text wrapping and spacing.|`normal`, `nowrap`, `pre`|

### **Best for:**

✔ Preventing text from breaking layouts and ensuring proper content display.

### **Example:**

```css
.overflow-text {
    width: 200px;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
}
```
