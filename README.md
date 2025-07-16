
# 📸 Polaroid Photo Booth

A fun and interactive web-based photo booth app that captures live webcam photos, adds creative filters and captions, and displays them in a Polaroid-style photo strip. You can even download the entire strip as an image!

## ✨ Features

- 🎥 Live webcam preview using WebRTC
- 🎨 Apply real-time CSS filters:
  - Grayscale
  - Sepia
  - Invert
  - Contrast boost
  - Brightness
  - Blur + Bright
  - Saturate
  - Hue Rotate
- 🖊️ Add custom captions with selectable fonts
- 🌈 Choose themed photo strip backgrounds:
  - Default
  - Bokeh
  - Wood
  - Gradient
- 📸 Capture photos and generate Polaroid-style layout
- 💾 Download the photo strip as a single image using `html2canvas`
- 🧹 Clear the strip and start again

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- WebRTC API (camera access)
- [html2canvas](https://github.com/niklasvh/html2canvas) (for exporting the photo strip)

## 📂 Project Files

```
📁 polaroid-photo-booth/
├── index.html               # Main HTML file
├── v729-noon-4a.jpg         # Default background image
├── 1600w-aWWISmI4pVI.webp   # Bokeh background
├── ch.png                   # Wood background
└── README.md                # Project documentation
```

> ⚠️ Make sure all image files are in the same directory as `index.html`.

## 🚀 How to Use

1. Clone or download the repository:

   ```bash
   git clone https://github.com/your-username/polaroid-photo-booth.git
   cd polaroid-photo-booth
   ```

2. Open `index.html` in your browser (Chrome recommended).

3. Allow webcam access when prompted.

4. Use the filters, captions, and background options to customize your photos.

5. Capture photos to add them to the Polaroid strip.

6. Click **Download Strip** to save your photo strip as an image.

## 📸 Live Demo

*(Optional: Add a link here if deployed on GitHub Pages or any other platform)*

## 📃 License

This project is licensed under the [MIT License](LICENSE).

---

Made with ❤️ for creativity and memories!
