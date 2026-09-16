# 🖼️ PixVault

> Transfer images as portable JSON files.

**PixVault** is a lightweight, frontend-only web tool that converts images into self-contained JSON files and reconstructs the original images from those JSON files.

No backend.  
No database.  
No account.  
No API key.  
Your files stay on your device.

---

## ✨ Features

- 🖼️ Image → JSON
- 📄 JSON → Image
- 📦 Embeds the image data directly inside the JSON
- 🔄 Reconstructs the original image
- 📱 Mobile friendly
- 💻 Desktop compatible
- 📤 Share JSON files directly
- 📤 Share reconstructed images
- 💾 Save files locally
- 📊 Displays image information
- 🔒 No server-side storage
- 🌐 Works entirely in the browser
- ⚡ Lightweight and fast

---

## 🧠 How It Works

PixVault converts the selected image into a Base64 Data URL and stores it inside a JSON structure.

```text
🖼️ Image
   ↓
Base64
   ↓
📄 PixVault JSON
   ↓
📤 Transfer
   ↓
📄 JSON
   ↓
Base64 → Image
   ↓
🖼️ Original Image
