# 🔍 Image Search Engine

A clean and responsive image search application built with **HTML**, **CSS**, and **JavaScript**, powered by the **Unsplash API**.

---

## 📸 Features

- 🔎 Search for high-quality images instantly
- 🖼️ Displays 12 results per page
- ➕ Load more images with "Show more" button
- 🌐 Clickable images open in a new tab on Unsplash
- 💡 Responsive and modern UI design

---

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript
- [Unsplash API](https://unsplash.com/developers)

---

### 3️⃣ Add Your API Key

Open `script.js` and paste your Unsplash Access Key:

```js
const accessKey = "YOUR_UNSPLASH_ACCESS_KEY_HERE";
```
---

## ▶️ Run the App

You can run this app by simply opening `index.html` in your browser:

```bash
Open with Live Server (VS Code) or double-click index.html
```

No build tools or server setup needed.

---

## 🧠 How It Works

- The app sends a request to the Unsplash API with your search query.  
- It receives a list of images in JSON format.  
- JavaScript dynamically generates image cards and appends them to the page.  
- Clicking "Show More" loads the next page of images.