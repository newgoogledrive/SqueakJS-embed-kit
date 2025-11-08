# SqueakJS Embed Kit

This kit lets you embed the **SqueakJS** virtual machine on any website — similar to how **Ruffle** embeds old Flash projects.

---

## 📁 Folder Layout

```
squeak-embed-kit/
│
├─ example.html
├─ README.md
└─ squeakjs/
├─ squeak.js
├─ images/
│ └─ example.image
└─ run/
├─ index.html
├─ squeak.css
└─ SqueakJS-logo.png
```

---

## 🚀 How to Use

1. Upload the entire `squeak-embed-kit` folder to your website or GitHub Pages.  
2. Place your `.image` file inside the `images/` folder.  
3. Add this HTML snippet to any page on your site:

```html
<iframe
  src="squeak-embed-kit/squeakjs/run/index.html#image=../images/YourImage.image"
  width="800"
  height="600"
  style="border:0;"
></iframe>
```

4. That’s it — the emulator will start and load your image automatically.

---

## 🧠 Notes
- Works on any static web host (GitHub Pages, Netlify, etc.)
- To update to a newer SqueakJS version, replace the `squeakjs/` folder with the latest one from the [official SqueakJS repository](https://github.com/squeak-smalltalk/squeakjs).
- You can include multiple images — just add them to the `images/` folder and adjust the iframe URL.

---

## 🧩 Example
Open `example.html` in your browser to see a working embedded SqueakJS frame.
