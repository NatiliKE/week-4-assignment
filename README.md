# CSS Box Model Example

## 📌 Overview
This project demonstrates the use of **HTML5 structure** and the **CSS Box Model**.  
It consists of a basic web page styled with an external CSS file.

---

## 📂 Files Included
- **index.html** → The main HTML file that contains the page structure.
- **styles.css** → External CSS file that applies styling to the elements.
- **README.md** → This documentation file.

---

## 🖥️ How It Works
1. Open `index.html` in a browser.
2. The `<h1>` element uses a CSS class `.main-head` for styling.
3. The `<p>` element uses a CSS ID `#intro` for styling.
4. Both elements are styled using the **CSS Box Model** properties:
   - **Margin** → Space outside the border.
   - **Border** → The visible edge around the element.
   - **Padding** → Space between content and border.
   - **Content** → The actual text inside the element.

---

## 🎨 Example CSS Styling
```css
.main-head {
    font-size: 2em;
    color: darkblue;
    text-align: center;
    margin: 20px;
    padding: 10px;
    border: 2px solid navy;
    background-color: lightyellow;
}

#intro {
    font-size: 1.2em;
    color: #333;
    margin: 20px;
    padding: 15px;
    border: 2px solid #444;
