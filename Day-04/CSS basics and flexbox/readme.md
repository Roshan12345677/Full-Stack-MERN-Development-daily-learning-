# 🎨 Day 04 - CSS Basics & Flexbox

📅 Date: 17 April 2026
🎯 Goal: Learn CSS fundamentals and layout using Flexbox

---

## 🌐 Topics Covered

* Introduction to CSS
* Types of CSS (Inline, Internal, External)
* CSS Selectors
* Colors & Backgrounds
* Fonts & Text Styling
* Display Property
* Flexbox (Layout System)

---

## 🔹 1. What is CSS?

CSS (Cascading Style Sheets) is used to style and design web pages.

👉 Think:

* HTML → Structure
* CSS → Styling
* JS → Logic

---

## 🔹 2. Types of CSS

### 1️⃣ Inline CSS

```html
<p style="color:red;">Hello</p>
```

❌ Not reusable
❌ Messy code

---

### 2️⃣ Internal CSS

```html
<style>
p {
  color: blue;
}
</style>
```

✔ Used for single page

---

### 3️⃣ External CSS ⭐ (Best Practice)

```html
<link rel="stylesheet" href="style.css">
```

✔ Reusable
✔ Clean & maintainable

---

## 🔹 3. CSS Selectors

```css
/* Element Selector */
p {
  color: red;
}

/* Class Selector */
.box {
  background-color: yellow;
}

/* ID Selector */
#header {
  color: green;
}

/* Universal Selector */
* {
  margin: 0;
}
```

👉 Priority: Inline > ID > Class > Tag

---

## 🔹 4. Colors in CSS

```css
color: red;
color: rgb(200, 98, 70);
color: #ff7180;
color: hsl(8, 90%, 63%);
```

✔ Supports RGBA & HSLA also

---

## 🔹 5. Background Properties

```css
body {
  background-color: lightblue;
  background-image: url("image.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
}
```

---

## 🔹 6. Fonts & Text Styling

```css
p {
  font-family: Arial, sans-serif;
  font-size: 24px;
  font-weight: bold;
  font-style: italic;
  text-align: center;
  text-decoration: underline;
  line-height: 1.5;
  letter-spacing: 2px;
}
```

---

## 🔹 7. Display Property

### 📦 Types:

```css
display: block;        /* full width */
display: inline;       /* only required width */
display: inline-block; /* inline + width/height allowed */
display: none;         /* hidden */
```

---

## 🔹 8. Flexbox (Most Important 🚀)

Flexbox is used to create layouts easily.

👉 Parent = Flex Container
👉 Children = Flex Items

---

### 🔸 Basic Flex

```css
.container {
  display: flex;
}
```

---

### 🔸 Flex Direction

```css
flex-direction: row;        /* default */
flex-direction: column;
flex-direction: row-reverse;
flex-direction: column-reverse;
```

---

### 🔸 Justify Content (Horizontal)

```css
justify-content: flex-start;
justify-content: flex-end;
justify-content: center;
justify-content: space-between;
justify-content: space-around;
justify-content: space-evenly;
```

---

### 🔸 Align Items (Vertical)

```css
align-items: flex-start;
align-items: center;
align-items: flex-end;
align-items: stretch;
```

---

### 🔸 Flex Wrap

```css
flex-wrap: wrap;
```

---

### 🔸 Gap (Spacing)

```css
gap: 10px;
```

---

### 🔸 Flex Item Properties

```css
.child {
  flex: 1;       /* equal width */
}

.child2 {
  flex: 2;       /* takes more space */
}
```

---

### 🔸 Order (Change Position)

```css
.box1 { order: 2; }
.box2 { order: 1; }
.box3 { order: 3; }
```

---

### 🔸 Align Self

```css
.item {
  align-self: center;
}
```

---

## 🧠 Key Learnings

* CSS makes websites visually attractive
* External CSS is best practice
* Flexbox simplifies layout design
* Selectors help target elements
* Display & Flexbox are core concepts

---

## 🔥 Progress Tracker

✅ Day 01 Completed
✅ Day 02 Completed
✅ Day 03 Completed
✅ Day 04 Completed
⏳ Day 05 Coming Soon...

