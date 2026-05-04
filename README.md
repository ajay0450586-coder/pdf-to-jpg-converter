# PDF to JPG Converter 🚀

Simple React + JavaScript + CSS app to upload PDF and convert pages to JPG images.

## 🎯 Features
- Upload PDF file (click or drag & drop)
- Auto-convert **all pages** to high-quality JPG (2x scale for sharpness)
- Live preview thumbnails
- Download individual JPGs or all JPGs batch
- Responsive design, loading states, error handling
- PDF.js worker fixed for reliable offline use

## 🚀 Quick Start
```

npm install
npm start
```
Open http://localhost:3000

## 📦 Production Build
```
npm run build
```
Serves static files from `./build/` folder.

## 🛠 Tech Stack
- React 18
- pdfjs-dist for PDF rendering
- Canvas API for JPG conversion
- file-saver for downloads
- Custom CSS (glassmorphism, gradients)

## 📱 Test It
1. Upload any PDF
2. Click \"Convert to JPG\"
3. Preview pages → Download

Handles multi-page PDFs perfectly!

## 🔧 Troubleshooting
- Worker error? `npm install` copies pdf.worker.min.js to public/
- Large PDFs? Higher scale/resolution adjustable in App.js

**Ready-to-use, no backend needed!** 🎉


