___
# CSS Pseudo-Classes: The Ultimate Guide

Pseudo-classes allow you to **style elements based on their state, position, or user interaction**, making CSS more dynamic without JavaScript.

---

## [ 1 ] Common Pseudo-Classes

|Pseudo-Class|Description|Example Usage|
|---|---|---|
|**`:focus`**|Styles an element when it gains keyboard or mouse focus.|`css input:focus { border: 2px solid blue; outline: none; }`|
|**`:hover`**|Styles an element when the user hovers over it.|`css button:hover { background-color: yellow; }`|
|**`:active`**|Styles an element when it is actively being clicked.|`css a:active { color: green; }`|
|**`:visited`**|Styles links that have been visited by the user.|`css a:visited { color: purple; }`|
|**`:link`**|Styles unvisited links.|`css a:link { color: blue; }`|
|**`:checked`**|Styles checkboxes and radio buttons when selected.|`css input:checked { accent-color: green; }`|
|**`:disabled`**|Styles elements that are disabled.|`css button:disabled { background-color: gray; }`|
|**`:enabled`**|Styles elements that are enabled.|`css input:enabled { border: 1px solid black; }`|
|**`:read-only`**|Targets form inputs that are read-only.|`css input:read-only { background: lightgray; }`|
|**`:read-write`**|Targets form inputs that are editable.|`css input:read-write { background: white; }`|
|**`:placeholder-shown`**|Styles input fields when their placeholder text is visible.|`css input:placeholder-shown { border-color: orange; }`|

---

## [ 2 ] Structural Pseudo-Classes

|Pseudo-Class|Description|Example Usage|
|---|---|---|
|**`:first-child`**|Selects the first child of a parent.|`css div:first-child { color: red; }`|
|**`:last-child`**|Selects the last child of a parent.|`css div:last-child { color: blue; }`|
|**`:nth-child(n)`**|Selects the nth child of a parent using a number or formula.|`css li:nth-child(odd) { background: lightblue; }`|
|**`:nth-last-child(n)`**|Selects the nth child from the end.|`css li:nth-last-child(2) { color: red; }`|
|**`:first-of-type`**|Selects the first element of its type within a parent.|`css p:first-of-type { font-weight: bold; }`|
|**`:last-of-type`**|Selects the last element of its type within a parent.|`css p:last-of-type { font-style: italic; }`|
|**`:nth-of-type(n)`**|Selects the nth element of a specific type.|`css span:nth-of-type(3) { text-decoration: underline; }`|
|**`:nth-last-of-type(n)`**|Selects the nth element of a type from the end.|`css div:nth-last-of-type(1) { border: 1px solid black; }`|
|**`:only-child`**|Selects an element if it is the **only** child of its parent.|`css div:only-child { color: green; }`|
|**`:only-of-type`**|Selects an element if it is the **only** of its type within a parent.|`css h1:only-of-type { font-size: 24px; }`|
|**`:empty`**|Selects elements that contain no children or text.|`css div:empty { background-color: lightgray; }`|

---

## [ 3 ] Form and Input Pseudo-Classes

|Pseudo-Class|Description|Example Usage|
|---|---|---|
|**`:valid`**|Styles inputs that meet validation criteria.|`css input:valid { border: 2px solid green; }`|
|**`:invalid`**|Styles inputs that fail validation.|`css input:invalid { border: 2px solid red; }`|
|**`:required`**|Targets input fields marked as required.|`css input:required { border-left: 4px solid red; }`|
|**`:optional`**|Targets input fields that are not required.|`css input:optional { border-left: 4px solid blue; }`|

---

## [ 4 ] Negation and Special Pseudo-Classes

|Pseudo-Class|Description|Example Usage|
|---|---|---|
|**`:not(selector)`**|Excludes specific elements from styling.|`css p:not(.special) { font-size: 14px; }`|
|**`:has(selector)`**|Selects elements that contain a specific child (experimental).|`css div:has(img) { border: 2px solid blue; }`|
|**`:where(selector)`**|Applies styles with **zero specificity**.|`css :where(h1, h2, h3) { font-weight: bold; }`|
|**`:is(selector)`**|Groups multiple selectors for easier styling.|`css :is(h1, h2, h3) { color: navy; }`|

---

## [ 5 ] Example: Styling Links with Pseudo-Classes

|Pseudo-Class|Effect|
|---|---|
|**`:link`**|Unvisited links appear **blue**.|
|**`:visited`**|Clicked links turn **purple**.|
|**`:hover`**|Links turn **red** when hovered.|
|**`:active`**|Links turn **green** when clicked.|

### **Example Usage:**

```css
a:link {
    color: blue;
}

a:visited {
    color: purple;
}

a:hover {
    color: red;
}

a:active {
    color: green;
}
```

---

## [ 6 ] Quick Tip

|Tip|Description|
|---|---|
|**Live Testing in Chrome**|Right-click an element → Select **Inspect** → Enable **:hover, :focus, or other states** under the Styles panel.|
