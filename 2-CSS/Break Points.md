To ensure your `.container` is optimized for **widely used screen sizes**, we can follow a well-structured approach based on real-world usage. Below are the **most commonly used breakpoints**, considering **Bootstrap's grid system** and modern device statistics:

---

### 📌 **Best Container Widths for Different Screen Sizes**

|Device Type|Breakpoint (min-width)|Suggested Max Container Width|
|---|---|---|
|**Extra Small (Mobile - Default)**|None (default styles)|`100%` (fluid, full width)|
|**Small (Landscape Phones)**|`576px`|`540px`|
|**Medium (Tablets)**|`768px`|`720px`|
|**Large (Laptops & Small Desktops)**|`992px`|`960px`|
|**Extra Large (Standard Desktops & Large Screens)**|`1200px`|`1140px`|
|**XX-Large (Widescreens, 4K Monitors)**|`1400px`|`1320px`|

---

### 🎨 **CSS for the Container:**

```css
/* Default (Mobile-first) */
.container {
  width: 100%;
  padding: 0 15px; /* Prevents content from touching edges */
  margin: 0 auto; /* Center align */
}

/* Small devices (576px and up) */
@media (min-width: 576px) {
  .container {
    max-width: 540px;
  }
}

/* Medium devices (768px and up) */
@media (min-width: 768px) {
  .container {
    max-width: 720px;
  }
}

/* Large devices (992px and up) */
@media (min-width: 992px) {
  .container {
    max-width: 960px;
  }
}

/* X-Large devices (1200px and up) */
@media (min-width: 1200px) {
  .container {
    max-width: 1140px;
  }
}

/* XX-Large devices (1400px and up) */
@media (min-width: 1400px) {
  .container {
    max-width: 1320px;
  }
}
```

---

### 📝 **Why These Values?**

✅ **Based on real-world usage** (Bootstrap & modern screen resolutions).  
✅ **Ensures readability & usability** on different devices.  
✅ **Uses a fluid approach** (full width on mobile, max width on larger screens).

Let me know if you need tweaks for a **specific project** or **custom breakpoints**! 🚀