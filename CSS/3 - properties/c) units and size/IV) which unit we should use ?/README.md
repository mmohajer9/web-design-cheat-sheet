# Which Units or Sizes Should We Use

At first , we need to specify where to use units and sizes.

units and values are used in :

1. font-sizes:

   - root element
   - body elements

2. Box Model:

   - margin
   - padding
   - border
   - height
   - width

3. Position elements: (Later Discuss)
   - top
   - bottom
   - left
   - right

---

## Recommendations for using Units and Values

---

1. In HTML Root element **`<html>`** , if you wanna to add the font-size to this tag , try <ins>**not to use**</ins> **`px`** for **`font-size`** and instead , use **`100%`** relative unit and it will derive its size from browser font-size setting

2. for elements and tags that are exist in **`body`** tag , try to use **`rem`** for **parent elements** and **`em`** for **child elements**.

3. in Box Model :

   - for **`margin`** and **`padding`** it is <ins>**recommended**</ins> to use **`rem`** and <ins>**do not use**</ins> **`px`**

   - for **`border`** , you should use **`px`**

   - for **`width`** and **`height`**, try to use **`percentage`** as far as possible. but beside **`percentage`** , you can use **`vw`** and **`vh`** and it can be applicable sometimes. and **the most important thing** is to <ins>try not to use</ins> **`px`** for these purpose.

   - for **`position`** , try to use **`percentage`** (check the next part)
