
---

## **[ 1 ] Parent Properties**

|Property|Description|Values & Notes|
|---|---|---|
|**`display`**|Defines a flex container.|`flex`|
|**`flex-direction`**|Defines the direction of flex items.|`row`, `row-reverse`, `column`, `column-reverse`|
|**`flex-wrap`**|Defines whether flex items wrap onto multiple lines.|`wrap`, `nowrap`|
|**Shorthand (`flex-flow`)**|Combines `flex-direction` and `flex-wrap`.|`flex-flow: wrap column-reverse;`|
|**`justify-content`**|Aligns items along the main axis.|`flex-start`, `flex-end`, `space-between`, `space-around`, `space-evenly`|
|**`align-items`**|Aligns items along the cross axis.|**Default:** `stretch` (if no height for children) Other values: `flex-start`, `center`, `flex-end`|
|**`gap`**|Creates spacing between flex items.|If `row`: **horizontal gap** If `column`: **vertical gap** If `wrap` exists: **both directions**|

---

## **[ 2 ] Child Properties (Flex Items)**

|Property|Description|Default Value|
|---|---|---|
|**`flex-grow`**|Determines how much an item can grow relative to others. Higher values allow more growth.|`0`|
|**`flex-shrink`**|Determines how much an item shrinks relative to others. Higher values allow more shrinking.|`0`|
|**`order`**|Defines the order of flex items. Lower values appear first.|`0`|
|**`flex-basis`**|Defines the default size of a flex item. Helps switch between width/height automatically when changing from `row` to `column`.|`auto`|
|**Shorthand (`flex`)**|Combines `flex-grow`, `flex-shrink`, and `flex-basis`.|`flex: 0 0 auto;`|
|**`align-self`**|Aligns an individual flex item within its container. Overrides `align-items`.|`auto`|

---

## **[ 3 ] Important Notes**

|Concept|Row Behavior|Column Behavior|
|---|---|---|
|**`justify-content`**|Aligns items **horizontally**.|Aligns items **vertically**.|
|**`align-items`**|Aligns items **vertically**.|Aligns items **horizontally**.|
