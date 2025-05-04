
```markdown
# 🧠 AR-PROJECT-01 - Augmented Reality with Marker Detection

This is a basic web-based Augmented Reality (AR) project built using **AR.js** and **A-Frame**, designed to display a 3D object (box) when a marker is detected using the device's camera.

---

## 🚀 Features

- Marker-based AR using `ar.js` and A-Frame.
- Web-based: Works directly in mobile or desktop browser.
- Local HTTPS server with camera access.
- Compatible with printed or digital marker (HIRO).

---

## 📁 Folder Structure

```

AR-PROJECT-01/
│
├── index.html          # Main AR webpage
├── assets/             # Folder for models, images, or audio (optional)
└── README.md           # Project documentation

````

---

## 🛠️ Prerequisites

- [Node.js](https://nodejs.org/)
- [ws](https://www.npmjs.com/package/ws) (simple HTTPS server for local use)
- Modern browser (Chrome, Firefox) with WebXR support
- Camera-enabled mobile phone or webcam

---

## 🧪 How to Run the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/IT21826740/AR-PROJECT-01.git
cd AR-PROJECT-01
````

### 2. Install `ws`

```bash
npm install -g ws
```

### 3. Run the Project with HTTPS

```bash
ws --https
```

You will see output like:

```
Listening on https://192.168.1.7:8000, https://127.0.0.1:8000, etc.
```

---

## 📱 View on Mobile

1. Connect your phone to the **same Wi-Fi network** as your PC.
2. Open the browser on your phone and enter the local IP shown (e.g.):

```
https://192.168.1.7:8000
```

3. Accept the **security warning** (your certificate is self-signed).
4. Allow **camera access**.
5. Point your camera at the **HIRO marker** (see below).

---

## 🎯 Marker: HIRO

Use the default AR.js marker called **HIRO**.

* View it here: [HIRO Marker PNG](https://raw.githubusercontent.com/AR-js-org/AR.js/master/three.js/examples/marker-training/examples/pattern-files/pattern-hiro.png)
* Or download the [Printable PDF version](https://chev.me/arjs-marker-training/examples/pattern-files/hiro.pdf)

You can:

* Print it.
* Or open it on another device screen.

---

## 📄 License

MIT License

---

## ✨ Credits

* Built using [A-Frame](https://aframe.io/)
* Powered by [AR.js](https://github.com/AR-js-org/AR.js)

```

