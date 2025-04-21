# 🗺️ Scrollable & Zoomable Map (HTML + JS)

This project is a simple, lightweight interactive map implemented in plain JavaScript, HTML, and CSS — no frameworks or libraries required.

It features:

- ✅ Drag-to-scroll (like Google Maps)
- ✅ Mouse wheel zoom (zoom in/out with scroll)
- ✅ Hidden scrollbars
- ✅ High-resolution map support (4096×3072 or more)
- ✅ Zoom centered on the mouse cursor

---

## 📦 Features

| Feature         | Description                                  |
|----------------|----------------------------------------------|
| Dragging       | Click and drag to pan around the map         |
| Zooming        | Scroll your mouse wheel to zoom in or out    |
| Scrollbars     | Hidden for a cleaner UI                      |
| Performance    | Smooth behavior with hardware acceleration   |
| Image Format   | Uses `<img>` tag to ensure pixel-perfect rendering |

---

## 🖼️ Demo Setup

Replace the image URL inside the `index.html` with your own map image (preferably 4096×3072 for best results):

```html
<img src="your-map-file.jpg" alt="Map">
```

You can also host your image locally, e.g.:

```html
<img src="images/my-map.jpg" alt="Map">
```

---

## 🚀 Getting Started

1. Clone or download this repo.
2. Place your map image in the project folder.
3. Open `index.html` in your browser.
4. Drag to move around, scroll to zoom in/out.

---

## 🔧 Customization

| Option         | How to Customize                                        |
|----------------|---------------------------------------------------------|
| Map Size       | Modify the `#map` width and height in `style.css`       |
| Zoom Limits    | Adjust `MIN_SCALE` and `MAX_SCALE` in the script        |
| Zoom Speed     | Change `ZOOM_FACTOR` (default: `0.1`)                   |
| Starting Zoom  | Modify `scale = 1` or change `transform` at load        |
| Centering      | Controlled by `window.onload` behavior                  |

---

## 🧪 Browser Compatibility

Tested in:

- ✅ Chrome
- ✅ Firefox
- ✅ Edge
- ✅ Safari

---

## 📜 License

MIT License – free to use, modify, and distribute.

---

## 🙋‍♂️ Author

Built with ❤️ and AI by Thomas Amar.

Feel free to fork, remix, or build on this!
