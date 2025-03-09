
---

## **[ 1 ] Parent Properties**

|Property|Description|Values & Notes|
|---|---|---|
|**`display`**|Creates a grid container.|`grid`, `inline-grid`|
|**`grid-template-columns`**|Defines **number of columns** and their widths.|`px`, `%`, `auto`, `repeat()`, `minmax()`, `fr`|
|**`grid-template-rows`**|Defines **number of rows** and their heights.|`px`, `%`, `auto`, `repeat()`, `minmax()`, `fr`|
|**`gap`**|Shorthand for `row-gap` and `column-gap`.|`gap: 1px;` (Applies to both)|
|**`grid-template-area`**|Defines named grid areas.|`"name name second second"` `"name name second second"` `"name name second second"`|
|**`grid-area` (for children)**|Assigns child elements to grid areas.|`grid-area: name;` `grid-area: second;`|

---

## **[ 2 ] Important Notes on Grid Parent Properties**

|Note|Description|Example|
|---|---|---|
|**Repeat Function**|Repeats the same value for columns/rows.|`repeat(number, value)`|
|**Auto vs. Fraction (`fr`)**|`auto` is **shy** (fits content), `fr` is **greedy** (takes remaining space).|-|
|**Auto-Fill**|Automatically adjusts columns based on container width.|`grid-template-columns: repeat(auto-fill, 200px);`|
|**Minmax Function**|Defines a range between **min** and **max** values.|`grid-template-columns: minmax(200px, 600px) repeat(2, 500px);`|

---

## **[ 3 ] Example for `minmax()`**

|Scenario|Behavior|
|---|---|
|**Container width = 1400px**|- Two `500px` columns → `1000px` total. - Remaining space = `400px`. - Since `400px` is **between `200px` and `600px`**, it takes `400px`.|
|**Container width ≥ 1600px**|The `minmax` column **returns to `600px`** (original max value).|

---

## **[ 4 ] Child Properties**

| Property          | Description                                                                    | Example Usage                                                                        |
| ----------------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| **`grid-column`** | Defines **column start and end** positions.                                    | `grid-column: start / end;` `grid-column: span 2;` (Ensures design stability)        |
| **`grid-row`**    | Defines **row start and end** positions.                                       | `grid-row: start / end;` `grid-row: span 3;`                                         |
| **`grid-area`**   | Defines **row-start, column-start, row-end, column-end** OR a named grid area. | `grid-area: row-start / column-start / row-end / column-end;` <br>`grid-area: name;` |

---

## **[ 5 ] Common Grid Layout Patterns**

|Layout|Description|Example|
|---|---|---|
|**Basic 2-Column Grid**|A simple two-column layout.|`grid-template-columns: 1fr 1fr;`|
|**3-Column Responsive Grid**|Adapts based on container width.|`grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));`|
|**Nested Grid**|Grid inside a grid for complex layouts.|`.parent { display: grid; }` `.child { display: grid; }`|

---

## **[ 6 ] Best Practices & Performance Tips**

|Best Practice|Reason|
|---|---|
|**Use `fr` instead of fixed widths**|Makes the layout **more flexible**.|
|**Combine Flexbox & Grid**|Use **Flexbox** for **small UI components** and **Grid** for **layouts**.|
|**Avoid `grid-template-rows: auto` for complex layouts**|Prevents **unexpected height issues**.|
|**Use `grid-template-areas` for semantic layouts**|Improves **readability & maintainability**.|

---

## **[ 7 ] Browser Support Notes**

|Feature|Browser Support|
|---|---|
|**Grid Basics (`display: grid`)**|✅ Supported in all modern browsers.|
|**`grid-template-areas`**|❌ **Not fully supported in IE11**.|
|**`auto-fill` & `auto-fit`**|⚠️ **Limited support in older browsers**.|
