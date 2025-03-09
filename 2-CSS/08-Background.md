
---

# CSS Background Properties: The Ultimate Guide

CSS provides various properties to **control the background appearance** of an element, allowing for **colors, images, positioning, and more**.

---

## [ 1 ] Background Properties – Defining Element Backgrounds

| Property                    | Description                                         | Example Values                                                                                         |
| --------------------------- | --------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| **`background-color`**      | Defines the background color.                       | `red`, `rgba(255, 255, 255, 1)`, `#hex`, `hsl()`                                                       |
| **`background-image`**      | Sets an image as the background.                    | `background-image: url("link");`<br>`background-image: linear-gradient(to right, red 30%, green 70%);` |
| **`background-repeat`**     | Controls repetition of the background image.        | `repeat`, `repeat-x`, `repeat-y`, `no-repeat`                                                          |
| **`background-attachment`** | Defines how the background behaves with scrolling.  | `scroll` (default), `fixed`                                                                            |
| **`background-position`**   | Sets the starting position of the background image. | `top`, `bottom`, `left`, `right`, `50px 100px`                                                         |
| **`background-size`**       | Defines the size of the background image.           | `auto`, `cover`, `contain`, `60px auto`                                                                |

### **Example Usage:**

```css
body {
  background-color: #f0f0f0;
  background-image: url("background.jpg");
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center top;
  background-size: cover;
}
```

---

## [ 2 ] Background Positioning

|Position Value|Description|
|---|---|
|**Keywords**|`top`, `bottom`, `left`, `right`, `top left`, `top right`, `bottom left`, `bottom right`|
|**Pixel Values**|`background-position: 50px 100px;`|
|**Percentage**|`background-position: 50% 50%;` (Centers the image)|

### **Example Usage:**

```css
.header {
  background-position: bottom right;
}

.card {
  background-position: 50px 100px;
}
```

---

## [ 3 ] Background Size

|Value|Description|
|---|---|
|**`auto`**|Default size (image keeps its original dimensions).|
|**`cover`**|Scales the image to cover the entire element (may crop).|
|**`contain`**|Scales the image to fit inside the element (may leave empty space).|
|**Fixed Size**|`background-size: 100px 50px;`|

### **Example Usage:**

```css
.banner {
  background-size: cover;
}

.logo {
  background-size: contain;
}
```

---

## [ 4 ] Background Shorthand – Combining Properties

Instead of setting each property separately, **use the shorthand** for a cleaner style declaration.

### **Syntax:**

```css
background: <color> <image> <position> / <size> <repeat> <attachment> <clip> <origin>;
```

|Property Included|Description|
|---|---|
|**`background-color`**|Defines the background color.|
|**`background-image`**|Sets the background image.|
|**`background-position`**|Specifies the position of the image.|
|**`background-size`**|Defines the image size (added using `/`).|
|**`background-repeat`**|Controls image repetition.|
|**`background-attachment`**|Determines scrolling behavior.|
|**`background-origin & background-clip`**|Defines the area covered.|

### **Example Usage:**

```css
.hero {
  background: #ffcc00 url("hero.jpg") center / cover no-repeat fixed;
}
```

---

## [ 5 ] Summary

|Topic|Key Takeaways|
|---|---|
|**Background Colors & Images**|Use `background-color`, `background-image`, and gradients.|
|**Background Positioning**|Control alignment with `background-position`.|
|**Background Size**|Use `cover`, `contain`, or fixed sizes for scaling.|
|**Background Shorthand**|Combine multiple properties for cleaner CSS.|
