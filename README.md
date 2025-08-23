# 🧊 StegoVault – Ultimate Steganography Web Vault 🔐

 **"Hide your secrets in plain sight."**  
**StegoVault** is a web-based steganography tool that allows users to securely encode secret messages inside image files and decode them later — with optional password protection, speech output, and a clean, interactive interface.

---


## 🧠 About the Project

**StegoVault** was built as a personal learning project during my web development internship to explore both frontend and backend development concepts. It combines **image processing** and **data hiding (steganography)** to create a practical, fun, and secure way to share private messages.

It was also my attempt to merge traditional development with **AI-assisted tools** for more productivity and creativity.

---

## 💡 Key Features

- 📷 **Upload image and encode message**
- 🔓 **Decode messages from encoded images**
- 🛡️ **Password-based double security**
- 🌙 **Dark Mode / Light Mode toggle**
- 🗣️ **Text-to-Speech playback of secret messages**
- 📱 **Mobile-responsive and clean UI**

---

## 📸 How It Works

🔐 **Encoding (Hide Message):**

1. Upload an image file (`.png` / `.jpg`)
2. Enter a secret message
3. Enter a password for protection
4. Click **Encode**
5. Download the newly generated **secret image**

🔍 **Decoding (Reveal Message):**

1. Upload the encoded image
2. Enter the password (if used)
3. Click **Decode**
4. Read or listen to the original message

📌 Uses the **LSB (Least Significant Bit)** steganography technique under the hood.

---

## 🛠️ Tech Stack – StegoVault

### 🌐 Frontend
- **HTML5** – for building the structure of the UI  
- **CSS3** – for styling, responsive design, dark/light mode support  
- **JavaScript (Vanilla JS)** – for interactivity, fetch API calls to backend, and handling file uploads/downloads  
- **Web Speech API** – to read out hidden messages (voice playback)  

---

### 🧠 Backend
- **Node.js** – runtime environment for running JavaScript on server  
- **Express.js** – lightweight backend framework to handle API routes (`/encode`, `/decode`)  
- **Multer** – middleware for handling file uploads (images)  
- **pngjs** – library for reading/writing PNG images at pixel level (used for encoding/decoding text)  
- **fs (File System)** – to manage image uploads, reading/writing encoded files  

---




