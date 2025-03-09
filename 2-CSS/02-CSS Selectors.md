# CSS Selectors

## 1. Part One: Basic Selectors

| Selector               | Description                                                                                                                                                                                                                                                                                                                                                                 |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `!important`           | `!important` rule **overrides all other CSS rules**, no matter their specificity or order in the stylesheet.                                                                                                                                                                                                                                                                |
| `*`                    | Universal Selector: Selects every single element on the page.                                                                                                                                                                                                                                                                                                               |
| `div`, `h2`, `p`       | Element Selector: Targets specific elements by name.                                                                                                                                                                                                                                                                                                                        |
| `div p`                | Descendant Selector: Selects any `<p>` inside a `<div>` (including children and grandchildren).                                                                                                                                                                                                                                                                             |
| `#my-div-id`           | The **ID selector (`#idName`)** is used to style a specific element with a given `id`.<br>An **ID selector has higher specificity** than class and element selectors. This means that **it will override any styles from class or element selectors, regardless of their order in the CSS file**, unless a more specific rule (like inline styles or `!important`) is used. |
| `.div-class`           | The **class selector (`.className`)** is used to style elements that have a specific class.<br>Even if the class selector appears **before** an element selector in the CSS file, it will still **only override styles for the properties it defines**. It does not completely replace the element's default styles or other styles applied by element selectors.           |
| `.div.my-p`            | Descendant Class Selector: Targets `<p>` elements inside a `.my-div-class` element.                                                                                                                                                                                                                                                                                         |
| `.my-p.my-p`           | Multiple Class Selector: Targets elements that have both `my-p-class` and `my-p-class2`.                                                                                                                                                                                                                                                                                    |
| `.class div, .class p` | Grouping Selector: Targets both `<div>` and `<p>` inside `.class-name`.                                                                                                                                                                                                                                                                                                     |
| `div.class`            | Element-Class Selector: Targets `<div>` elements with `class-name`.                                                                                                                                                                                                                                                                                                         |
| `.parent > .child`     | Direct Child Selector: Targets direct children (not grandchildren).                                                                                                                                                                                                                                                                                                         |
| `.parent > *`          | Universal Direct Children Selector: Targets All direct children (not grandchildren).                                                                                                                                                                                                                                                                                        |
___
## 2. Part Two: Adjacent and Attribute Selectors

### **Adjacent Selectors**

| Selector  | Description                                                                                      |
| --------- | ------------------------------------------------------------------------------------------------ |
| `p + p`   | Adjacent Sibling Selector: Selects every `<p>` that directly followed by another `<p>`.          |
| `p ~ div` | General Sibling Selector: Targets all `<div>` elements that come after a `<p>` and are siblings. |

### **Attribute Selectors**

| Selector               | Description                                                                  |
| ---------------------- | ---------------------------------------------------------------------------- |
| `[title]`              | Selects elements with the `title` attribute.                                 |
| `div[title]`           | Selects `<div>` elements with the `title` attribute.                         |
| `[title="S01"]`        | Selects elements where `title` is exactly `S01`.                             |
| `input[type="search"]` | Selects `<input>` elements of type `search`.                                 |
| `[title~="text"]`      | Selects elements where `title` contains the word `text` as a separate value. |
| `[title*="Text"]`      | Selects elements where `title` contains `Text` anywhere in the value.        |
| `[title^="S0"]`        | Selects elements where `title` starts with `S0`.                             |
___
## 3. Part Three: Child and Type Selectors

|Selector|Description|
|---|---|
|`:first-child`|Selects the first child of its parent.|
|`:last-child`|Selects the last child of its parent.|
|`p:first-of-type`|Selects the first `<p>` of its type inside any parent.|
|`p:last-of-type`|Selects the last `<p>` of its type inside any parent.|
|`p:only-child`|Selects `<p>` if it is the only child of its parent.|
|`p:only-of-type`|Selects `<p>` if it is the only `<p>` inside its parent.|
___
## 4. Part Four: Advanced Selectors

|Selector|Description|
|---|---|
|`p:not(:first-child)`|Selects all `<p>` elements except the first child.|
|`p:not(.class-name)`|Selects all `<p>` elements except those with `.class-name`.|
|`:nth-child(n)`|Selects the nth child of its parent (supports `even`, `odd`).|
|`:nth-last-child(n)`|Selects the nth child from the end.|
|`:nth-of-type(n)`|Selects the nth element of its type.|
|`:nth-last-of-type(n)`|Selects the nth element of its type from the end.|
___
## 5. Part Five: Pseudo-classes and Pseudo-elements

### **State-based Selectors**

- `:root` - Selects the root element (`<html>`).
- `:checked` - Selects checked inputs (`radio`, `checkbox`).
- `:empty` - Selects elements with no children.
- `:disabled` - Selects disabled form elements.
- `:required` - Selects required form elements.
- `:focus` - Selects an element when focused.
- `:active` - Selects an element while being clicked.
- `:hover` - Selects an element when hovered.
- `:visited` - Selects visited links.
- `:link` - Selects unvisited links.

### **Pseudo-elements**

- `::selection` - Styles selected text.
- `::placeholder` - Styles the placeholder text in inputs.

___
