
---

## [ 1 ] Fixed – Absolute Units

| Unit   | Description                                                                      | Notes                           |
| ------ | -------------------------------------------------------------------------------- | ------------------------------- |
| **px** | Pixels : are the most commonly used unit for fixed dimensions in digital design. | Used in web and UI design.      |
| **cm** | Centimeters : are a real-world measurement, mostly used for print.               | 1cm = 10mm                      |
| **mm** | Millimeters : are smaller print unit.                                            | 10mm = 1cm                      |
| **in** | Inches : are units where **1 inch = 96 pixels**.                                 | Common in print design.         |
| **pt** | Points : are used in typography, where **1pt = 1/72 inch**.                      | Mainly for text in print media. |
| **pc** | Picas : are print layout unit, **1 pica = 12 points**.                           | Used in publishing.             |

✅ **Best for:** Fixed UI elements, print design, and when exact dimensions are required.

### **Example:**

```css
.fixed-box {
    width: 300px;  /* Will not change with screen size */
    height: 200px;
}
```

---

## [ 2 ] Relative Units (Flexible & Responsive)

| Unit     | Description                                                             | Notes                             |
| -------- | ----------------------------------------------------------------------- | --------------------------------- |
| **%**    | Percentage : Defines sizes relative to the parent element’s dimensions. | Good for fluid layouts.           |
| **em**   | Relative to the element’s own font size.                                | `1.5em` = 1.5 × parent font size. |
| **rem**  | Relative to the `<html>` font size.                                     | `1rem = root font size`.          |
| **vw**   | Viewport Width : `1vw = 1%` of the viewport width.                      | Used for full-width elements.     |
| **vh**   | Viewport Height : `1vh = 1%` of the viewport height.                    | Used for full-screen layouts.     |
| **vmin** | Takes the **smaller** value between `vw` and `vh`.                      | Helps with responsive elements.   |
| **vmax** | Takes the **larger** value between `vw` and `vh`.                       | Ensures elements scale properly.  |
| **ch**   | Relative to the width of the `"0"` character in the font.               | Useful for text layout.           |
| **ex**   | Based on the height of lowercase `"x"` in the font.                     | Less commonly used.               |

✅ **Best for:** Responsive typography, flexible layouts, mobile-friendly designs.

### **Example:**

```css
.flexible-box {
    width: 50%;   /* Takes half of the parent element’s width */
    height: 30vh; /* Occupies 30% of the viewport height */
}
```

---

## 🌟 Final Thoughts

|Tip|Description|
|---|---|
|**Use `px`**|For precise control over elements.|
|**Use `em` & `rem`**|For scalable typography.|
|**Use `vh` & `vw`**|For full-screen layouts.|
|**Use `%`**|For fluid layouts.|
