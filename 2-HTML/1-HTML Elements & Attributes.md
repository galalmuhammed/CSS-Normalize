
Here’s an example for each of the **110 HTML elements**, organized by their categories:

---

### **1. Document Structure**

- **`<!DOCTYPE>`**: Declares the document type. (Neither, it is not an HTML element)
- **`<html>`**: Root element of an HTML document. (Block)
- **`<head>`**: Contains metadata about the document. (Block)
- **`<title>`**: Sets the title of the document (shown in the browser tab). (Inline)
- **`<body>`**: Contains the content of the document. (Block)

---

### **2. Metadata and Links**

- **`<base>`**: Specifies the base URL for relative URLs. (Inline)
- **`<link>`**: Defines relationships between the document and external resources (e.g., stylesheets). (Inline)
- **`<meta>`**: Defines metadata about the document (e.g., charset, viewport). (Inline)
- **`<style>`**: Embeds CSS styles in the document. (Block)

| **Element** | **Attribute** | **Description**                                            |
| ----------- | ------------- | ---------------------------------------------------------- |
| `<base>`    | `href`        | Base URL for relative links.                               |
| `<meta>`    | `charset`     | Declares character encoding (e.g., `UTF-8`).               |
|             | `name`        | Name of metadata (e.g., `viewport`, `description`).        |
|             | `content`     | Value of metadata.                                         |
|             | `http-equiv`  | Equivalent HTTP header (`refresh`, `Content-Type`).        |
| `<link>`    | `rel`         | Relationship between current document and linked resource. |
|             | `href`        | URL of the linked resource.                                |
|             | `type`        | Specifies the MIME type of the linked resource.            |
| `<style>`   | `type`        | Specifies the style type (e.g., `text/css`).               |

---

### **3. Sectioning Elements**

- **`<header>`**: Defines introductory content. (Block)
- **`<nav>`**: Represents navigation links. (Block)
- **`<main>`**: Indicates the main content. (Block)
- **`<section>`**: Groups content by theme. (Block)
- **`<article>`**: Represents independent content (e.g., blog posts). (Block)
- **`<aside>`**: Denotes side content (e.g., sidebar). (Block)
- **`<footer>`**: Defines footer content. (Block)
- **`<address>`**: Provides contact information. (Block)

---

### **4. Text Content**

- **`<p>`**: Represents a paragraph. (Block)
- **`<h1>` – `<h6>`**: Defines headings (level 1–6). (Block)
- **`<blockquote>`**: Denotes a block of quoted text. (Block)
- **`<cite>`**: References the title of a work. (Inline)
- **`<q>`**: Denotes inline quotes. (Inline)
- **`<abbr>`**: Represents abbreviations. (Inline)
- **`<acronym>`** _(deprecated)_: Use `<abbr>` instead. (Inline)
- **`<dfn>`**: Marks a term being defined. (Inline)
- **`<address>`**: Provides contact information. (Block)
- **`<time>`**: Represents a specific time or duration. (Inline)
- **`<code>`**: Displays inline code snippets. (Inline)
- **`<pre>`**: Represents preformatted text. (Block)
- **`<var>`**: Represents a variable in programming. (Inline)
- **`<samp>`**: Represents sample output. (Inline)
- **`<kbd>`**: Represents user input (e.g., keyboard keys). (Inline)
- **`<mark>`**: Highlights text. (Inline)
- **`<del>`**: Denotes deleted text. (Inline)
- **`<ins>`**: Denotes inserted text. (Inline)
- **`<small>`**: Represents fine print. (Inline)
- **`<strong>`**: Indicates strong importance. (Inline)
- **`<em>`**: Denotes emphasized text. (Inline)
- **`<b>`**: Represents stylistically bold text. (Inline)
- **`<i>`**: Represents stylistically italicized text. (Inline)
- **`<u>`**: Underlines text. (Inline)
- **`<s>`**: Represents text that is no longer accurate or relevant. (Inline)
- **`<bdi>`**: Isolates a part of text for bidirectional text formatting. (Inline)
- **`<bdo>`**: Overrides the current text direction. (Inline)

|**Element**|**Attribute**|**Description**|
|---|---|---|
|`<blockquote>`|`cite`|URL of the source.|
|`<q>`|`cite`|URL of the source.|
|`<abbr>`|`title`|Full term being abbreviated.|
|`<time>`|`datetime`|Machine-readable date/time.|
|`<del>`|`cite`, `datetime`|Source and timestamp for the deletion.|
|`<ins>`|`cite`, `datetime`|Source and timestamp for the insertion.|

---

### **5. Grouping Content**

- **`<div>`**: Defines a container for content. (Block)
- **`<span>`**: Represents inline content. (Inline)
- **`<hr>`**: Denotes a thematic break (horizontal rule). (Block)
- **`<br>`**: Inserts a line break. (Inline)

---

### **6. Lists**

- **`<ul>`**: Defines an unordered list. (Block)
- **`<ol>`**: Defines an ordered list. (Block)
- **`<li>`**: Represents a list item. (Block)
- **`<dl>`**: Defines a description list. (Block)
- **`<dt>`**: Represents a term in a description list. (Block)
- **`<dd>`**: Represents a description in a description list. (Block)

| **Element** | **Attribute** | **Description**                                                                      |
| ----------- | ------------- | ------------------------------------------------------------------------------------ |
| `<ul>`      | `type`        | Specifies the bullet style for an unordered list (e.g., `circle`, `disc`, `square`). |
| `<ol>`      | `type`        | Specifies the numbering style for an ordered list (e.g., `1`, `A`, `a`, `I`).        |
|             | `start`       | Specifies the starting number for an ordered list.                                   |
|             | `reversed`    | Reverses the order of the list items.                                                |
| `<li>`      | `value`       | Specifies the value of a list item in an ordered list when the list is numbered.     |

---

### **7. Tables**

- **`<table>`**: Defines a table. (Block)
- **`<thead>`**: Groups header content in a table. (Block)
- **`<tbody>`**: Groups body content in a table. (Block)
- **`<tfoot>`**: Groups footer content in a table. (Block)
- **`<tr>`**: Defines a row in a table. (Block)
- **`<th>`**: Defines a header cell in a table. (Inline)
- **`<td>`**: Defines a data cell in a table. (Inline)
- **`<caption>`**: Adds a caption to a table. (Block)
- **`<col>`**: Specifies column properties for a table. (Inline)
- **`<colgroup>`**: Groups columns in a table. (Block)

| **Element**    | **Attribute** | **Description**                                                                                                                                                                                          |
| -------------- | ------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `<table>`      | `border`      | Specifies the border width of the table.                                                                                                                                                                 |
|                | `cellspacing` | Specifies the space between table cells.                                                                                                                                                                 |
|                | `cellpadding` | Specifies the space between the content and the border of the cell.                                                                                                                                      |
| `<th>`, `<td>` | `scope`       | Specifies whether a header cell is for a row, column, or group of rows or columns.                                                                  usually `<th scope = "col">` and `td scope = "row"`. |
|                | `colspan`     | Specifies the number of columns a cell should span.                                                                                                                                                      |
|                | `rowspan`     | Specifies the number of rows a cell should span.                                                                                                                                                         |
| `<col>`        | `span`        | Specifies how many columns a column group should span.                                                                                                                                                   |
| `<colgroup>`   | `span`        | Specifies how many columns a column group should span.                                                                                                                                                   |

---

### **8. Forms**

- **`<form>`**: Represents a form. (Block)
- **`<input>`**: Defines an input field. (Inline)
- **`<textarea>`**: Represents a multiline text input field. (Inline)
- **`<button>`**: Represents a clickable button. (Inline)
- **`<select>`**: Defines a dropdown list. (Inline)
- **`<option>`**: Defines an option in a dropdown list. (Inline)
- **`<optgroup>`**: Groups options in a dropdown list. (Inline)
- **`<label>`**: Associates a label with a form control. (Inline)
- **`<fieldset>`**: Groups related elements in a form. (Block)
- **`<legend>`**: Represents a caption for a `<fieldset>`. (Inline)
- **`<datalist>`**: Defines a list of predefined options for an input. (Inline)
- **`<output>`**: Represents the result of a calculation or user action. (Inline)
- **`<progress>`**: Represents a progress bar. (Inline)
- **`<meter>`**: Represents a measurement within a range. (Inline)
Here's the updated table with the additional rows for the `type` attribute under `<input>` and a new row under `<datalist>` with its attributes:

| **Element**  | **Attribute**  | **Description**                                                                                                                                                                                             |
| ------------ | -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `<form>`     | `action`       | Specifies the URL to send the form data when the form is submitted.                                                                                                                                         |
|              | `method`       | Defines the HTTP method (GET or POST) to use when sending form data, GET for showing the info in the URL and POST will hide it in the URL.                                                                  |
|              | `novalidate`   | This attribute helps during testing that you don't have to add any information or validation during the testing.                                                                                            |
|              | `target`       | Specifies where to display the response (e.g., `_blank`, `_self`).                                                                                                                                          |
|              | `enctype`      | Specifies the encoding type for form data (used for file uploads).                                                                                                                                          |
| `<label>`    | `for`          | Associates the label with a specific form control (input, select, etc.).                                                                                                                                    |
| `<input>`    | `type`         | Specifies the input field type (text, tel, number, password, range, radio, checkbox, date, time, search, color, button, hidden, file, submit, reset).                                                       |
|              | `id`           | Using the same value in the label `for` attribute to link the input form with the label                                                                                                                     |
|              | `value`        | Specifies the initial value of the input field. Without it, the input will be sent to the backend without a value.                                                                                          |
|              | `name`         | Specifies the name of the input element, used to reference form data after submission. Without it, the data won't be sent to the backend.                                                                   |
|              | `placeholder`  | Specifies a short hint that describes the expected value of the input field.                                                                                                                                |
|              | `autocomplete` | Specifies whether you want the form to remember the last choices or not by default it's value is  `on`                                                                                                      |
|              | `required`     | Specifies whether this field is required or not and without it's value the form won't be submitted.                                                                                                         |
|              | `autofocus`    | Specifies the input field that should be focused on when the page loads.                                                                                                                                    |
|              | `readonly`     | Specifies that the user cannot edit the value after it is set.                                                                                                                                              |
|              | `disabled`     | Specifies that the input is disabled, so it won't be sent to the backend or updated.                                                                                                                        |
|              | `minlength`    | Sets the minimum length for the input value (e.g., password `minlength="8"`).                                                                                                                               |
|              | `maxlength`    | Sets the maximum length for the input value (e.g., password `maxlength="16"`).                                                                                                                              |
|              | `checked`      | Specifies whether a checkbox or radio button is checked by default.                                                                                                                                         |
|              | `list`         | Specifies a `<datalist>` element to provide predefined options for the input field. (like a variable name and you can use the same name inside the `id` for the `<datalist>`).                              |
| `<datalist>` | `id`           | Specifies a unique identifier for the `<datalist>` element, which can be referenced by the `list` attribute in `<input>`.                                                                                   |
| `<option>`   | `value`        | Defines a set of `<option>` elements inside the `<datalist>` element with a `value` for each. And `<option>` inside a `<datalist>` is a self closing tag and takes the name of the option from it's `value` |
| `<textarea>` | `rows`         | Specifies the number of visible text lines in the text area.                                                                                                                                                |
|              | `cols`         | Specifies the visible width of the text area in characters.                                                                                                                                                 |
|              | `placeholder`  | Specifies a short hint for the expected input in a textarea.                                                                                                                                                |
| `<button>`   | `type`         | Specifies the type of button (e.g., `submit`, `reset`, `button`).                                                                                                                                           |
|              | `name`         | Specifies the name of the button, used for referencing form data.                                                                                                                                           |
|              | `value`        | Specifies the value associated with the button.                                                                                                                                                             |
| `<select>`   | `name`         | Specifies the name of the dropdown, used to reference form data after submission.                                                                                                                           |
|              | `multiple`     | Allows multiple options to be selected in the dropdown.                                                                                                                                                     |
|              | `size`         | Specifies how many option should displayed at once                                                                                                                                                          |
| `<option>`   | `value`        | Specifies the value to be sent when the option is selected.       here you need to add the closing tag and in between you add the name of the option unlike the `<option>` inside the `<datalist>`          |
|              | `selected`     | Specifies whether an option is selected by default.                                                                                                                                                         |
| `<optgroup>` | `label`        | Specifies a label for the group of options within a dropdown.                                                                                                                                               |
| `<progress>` | `value`        | Specifies the current progress value of the progress bar.                                                                                                                                                   |
|              | `max`          | Specifies the maximum value of the progress bar.                                                                                                                                                            |
| `<meter>`    | `value`        | Specifies the current value of the measurement.                                                                                                                                                             |
|              | `min`          | Specifies the minimum value of the measurement.                                                                                                                                                             |
|              | `max`          | Specifies the maximum value of the measurement.                                                                                                                                                             |


---

### **9. Embedded Content**

- **`<img>`**: Embeds an image. (Inline)
- `<figure>`: Adding A Semantic meaning for the `<img>`.
- `<figcaption>`:Adding a caption for the images either before or after
- **`<iframe>`**: Embeds another document. (Inline)
- **`<embed>`**: Embeds external content (e.g., plugins). (Inline)
- **`<object>`**: Embeds multimedia or applications. (Inline)
- **`<param>`**: Defines parameters for an `<object>`. (Inline)
- **`<video>`**: Embeds a video. (Block)
- **`<audio>`**: Embeds an audio file. (Inline)
- **`<source>`**: Specifies media resources for `<video>` or `<audio>`. (Inline)
- **`<track>`**: Defines text tracks for `<video>` or `<audio>`. (Inline)

| **Element**   | **Attribute** | **Description**                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| ------------- | ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `<img>`       | `src`         | Specifies the URL of the image.                                                                                                                                                                                                                                                                                                                                                                                                                         |
|               | `alt`         | Provides alternative text for accessibility or if the image cannot be loaded.                                                                                                                                                                                                                                                                                                                                                                           |
|               | `width`       | Specifies the width of the image in pixels or percent.                                                                                                                                                                                                                                                                                                                                                                                                  |
|               | `height`      | Specifies the height of the image in pixels or percent.                                                                                                                                                                                                                                                                                                                                                                                                 |
|               | `loading`     | Default is `eager` (loads immediately). The `lazy` value delays loading until necessary, improving performance.                                                                                                                                                                                                                                                                                                                                         |
| `<figure>`    |               | Specifies a container that contains an `<img>` and `<figcaption>`                                                                                                                                                                                                                                                                                                                                                                                       |
| `<figcaption` |               | Specifies a caption of the `<img>` inside the container `<figure>`                                                                                                                                                                                                                                                                                                                                                                                      |
| `<iframe>`    | `src`         | Specifies the URL of the embedded document.                                                                                                                                                                                                                                                                                                                                                                                                             |
|               | `width`       | Specifies the width of the iframe.                                                                                                                                                                                                                                                                                                                                                                                                                      |
|               | `height`      | Specifies the height of the iframe.                                                                                                                                                                                                                                                                                                                                                                                                                     |
|               | `frameborder` | Specifies whether the iframe should have a border (deprecated; use CSS).                                                                                                                                                                                                                                                                                                                                                                                |
|               | `sandbox`     | Applies restrictions to the content within the iframe (e.g., disabling forms or scripts).                                                                                                                                                                                                                                                                                                                                                               |
| `<embed>`     | `src`         | Specifies the URL of the embedded content.                                                                                                                                                                                                                                                                                                                                                                                                              |
|               | `type`        | Specifies the MIME type of the embedded content.                                                                                                                                                                                                                                                                                                                                                                                                        |
|               | `width`       | Specifies the width of the embedded content.                                                                                                                                                                                                                                                                                                                                                                                                            |
|               | `height`      | Specifies the height of the embedded content.                                                                                                                                                                                                                                                                                                                                                                                                           |
| `<object>`    | `data`        | Specifies the URL of the embedded media.                                                                                                                                                                                                                                                                                                                                                                                                                |
|               | `type`        | Specifies the MIME type of the embedded media.                                                                                                                                                                                                                                                                                                                                                                                                          |
|               | `width`       | Specifies the width of the object.                                                                                                                                                                                                                                                                                                                                                                                                                      |
|               | `height`      | Specifies the height of the object.                                                                                                                                                                                                                                                                                                                                                                                                                     |
| `<param>`     | `name`        | Specifies the name of a parameter for the object.                                                                                                                                                                                                                                                                                                                                                                                                       |
|               | `value`       | Specifies the value of a parameter for the object.                                                                                                                                                                                                                                                                                                                                                                                                      |
| `<video>`     | `src`         | Specifies the video file URL.                                                                                                                                                                                                                                                                                                                                                                                                                           |
|               | `width`       | Specifies the width of the video player.                                                                                                                                                                                                                                                                                                                                                                                                                |
|               | `height`      | Specifies the height of the video player.                                                                                                                                                                                                                                                                                                                                                                                                               |
|               | `controls`    | Displays playback controls (e.g., play, pause, volume).                                                                                                                                                                                                                                                                                                                                                                                                 |
|               | `autoplay`    | Specifies that the video should play automatically.                                                                                                                                                                                                                                                                                                                                                                                                     |
|               | `muted`       | Mutes the video by default.                                                                                                                                                                                                                                                                                                                                                                                                                             |
|               | `loop`        | Repeats the video automatically.                                                                                                                                                                                                                                                                                                                                                                                                                        |
|               | `poster`      | Specifies an image to be displayed before the video plays.                                                                                                                                                                                                                                                                                                                                                                                              |
| `<audio>`     | `src`         | Specifies the audio file URL.                                                                                                                                                                                                                                                                                                                                                                                                                           |
|               | `controls`    | Displays playback controls for the audio.                                                                                                                                                                                                                                                                                                                                                                                                               |
|               | `autoplay`    | Specifies that the audio should play automatically.                                                                                                                                                                                                                                                                                                                                                                                                     |
|               | `muted`       | Specifies that the audio should play automatically.                                                                                                                                                                                                                                                                                                                                                                                                     |
|               | `loop`        | Repeats the audio automatically.                                                                                                                                                                                                                                                                                                                                                                                                                        |
| `<source>`    | `src`         | Specifies the URL of the media file. when adding the `source` you add it inside the `<audio>` or `<video>` element and you add the `src` attribute to the `<source>` element only.                 And you can add more than one `src` inside  the `<audio>` or `<video>` with a different `type` attribute. and you can add a text incase the `<audio>` or `<video>` were not supported like `Your browser does not support the video element.` after. |
|               | `type`        | Specifies the MIME type of the media file.                                                                                                                                                                                                                                                                                                                                                                                                              |
| `<track>`     | `src`         | Specifies the URL of the text track file.                                                                                                                                                                                                                                                                                                                                                                                                               |
|               | `kind`        | Specifies the type of text track (e.g., subtitles, captions).                                                                                                                                                                                                                                                                                                                                                                                           |
|               | `srclang`     | Specifies the language of the text track.                                                                                                                                                                                                                                                                                                                                                                                                               |
|               | `label`       | Provides a label for the text track.                                                                                                                                                                                                                                                                                                                                                                                                                    |

Everything is now properly formatted, with descriptions completed where they were cut off. Let me know if you need any modifications! 🚀
---

### **10. Interactive Elements**

- **`<a>`**: Defines a hyperlink. (Inline)
- **`<button>`**: Represents a clickable button. (Inline)
- **`<details>`**: Creates a collapsible content section. (Block)
- **`<summary>`**: Provides a summary for `<details>`. (Inline)
- **`<dialog>`**: Represents a dialog box or window. (Block)

| **Element**     | **Attribute** | **Description**                                                                                                                                                                                                                                                                                            |
| --------------- | ------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `<a>`           | `href`        | Specifies the URL of the hyperlink's destination.                                  You can use "mailto:email" to send it directly to your email.               also "tel:+20111111111" to directly make a phone call.                      and to another HTML page or use "/" to go back to the root HTML |
|                 | `target`      | Specifies where to open the link (e.g., `_blank` for a new tab).                                                                                                                                                                                                                                           |
|                 | `download`    | Specifies that the link should download a file instead of navigating to it.                                                                                                                                                                                                                                |
|                 | `rel`         | Specifies the relationship between the current document and the linked document (e.g., `nofollow`).                                                                                                                                                                                                        |
|                 | `type`        | Specifies the MIME type of the linked resource.                                                                                                                                                                                                                                                            |
| `<button>`      | `type`        | Specifies the button type: `submit`, `reset`, or `button`.                                                                                                                                                                                                                                                 |
|                 | `disabled`    | Disables the button, preventing user interaction.                                                                                                                                                                                                                                                          |
|                 | `name`        | Specifies the name of the button for form data submission.                                                                                                                                                                                                                                                 |
|                 | `value`       | Specifies the value associated with the button for form data submission.                                                                                                                                                                                                                                   |
| `<details>`     |               | Creates a collapsible content section.                                                                                                                                                                                                                                                                     |
| **`<summary>`** |               | Provides a summary for `<details>`. summary is like a caption or a title for the collapsible like a question and you click on it to reveal the answer and when you add a `<p>` inside it that should contain the answer.                                                                                   |
| **`<details>`** | `open`        | Specifies that the collapsible content should be visible (expanded) by default.                                                                                                                                                                                                                            |
| `<dialog>`      | `open`        | Specifies that the dialog box should be displayed (visible) by default.                                                                                                                                                                                                                                    |

---

### **11. Scripting**

- **`<script>`**: Embeds or references JavaScript. (Block)
- **`<noscript>`**: Provides fallback content when scripts are disabled. (Block)
- **`<template>`**: Defines a reusable template. (Block)
- **`<slot>`**: Defines placeholders inside Web Components. (Inline)

| **Element** | **Attribute** | **Description**                                                                                  |
| ----------- | ------------- | ------------------------------------------------------------------------------------------------ |
| `<script>`  | `src`         | Specifies the URL of an external script file.                                                    |
|             | `type`        | Specifies the MIME type of the script (e.g., `text/javascript`).                                 |
|             | `async`       | Executes the script asynchronously as soon as it is downloaded.                                  |
|             | `defer`       | Defers script execution until after the HTML document has been parsed.                           |
|             | `crossorigin` | Specifies whether the script can be fetched using CORS (e.g., `anonymous` or `use-credentials`). |
|             | `integrity`   | Ensures the script's integrity using a hash value for security purposes.                         |
| `<slot>`    | `name`        | Specifies a name for the slot, allowing content to be inserted into specific placeholders.       |

---

### **12. Obsolete/Deprecated Elements**

##### These are no longer recommended but may appear in older code:

- **`<acronym>`**: Use `<abbr>` instead. (Inline)
- **`<applet>`**: Use `<object>` instead. (Block)
- **`<bgsound>`**: (Inline)
- **`<basefont>`**: (Inline)
- **`<big>`**: (Inline)
- **`<center>`**: (Block)
- **`<font>`**: (Inline)
- **`<strike>`**: (Inline)
- **`<tt>`**: (Inline)

---
