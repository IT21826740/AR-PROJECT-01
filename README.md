

# AR-PROJECT-01

**AR-PROJECT-01** is a lightweight browser-based Augmented Reality (AR) web application that overlays 3D models on real-world markers using your device's camera. Built using **AR.js** and **A-Frame**, it enables seamless marker-based AR experiences directly from the browser without the need for any native app installation.

## 🌟 Features

* 🎯 Marker-based AR using HIRO marker
* 📱 Works across mobile and desktop browsers
* 🚀 Lightweight and fast performance (WebXR & WebGL)
* 🔒 HTTPS-ready local development for camera access
* 📦 Easy to host and extend with new 3D models

## 🔧 Technologies Used

### Frontend

* HTML, CSS, JavaScript
* A-Frame (WebVR/AR Framework)
* AR.js (Marker-based AR Engine)

### Others

* `ws` - Lightweight HTTPS server for local AR testing
* HIRO marker (Default AR marker provided by AR.js)

## 📁 Project Structure

```
AR-PROJECT-01/
│
├── index.html          # Main AR scene with marker tracking
├── assets/             # Folder for 3D models or images (if used)
└── README.txt          # Project documentation
```

---

## 🛠️ Steps to Run the Project

1️⃣ **Install Node.js**

Download and install Node.js from:
[https://nodejs.org](https://nodejs.org)

2️⃣ **Install the HTTPS Web Server (`ws`)**

```bash
npm install -g ws
```

3️⃣ **Clone the Repository**

```bash
git clone https://github.com/IT21826740/AR-PROJECT-01.git
cd AR-PROJECT-01
```

4️⃣ **Start the HTTPS Server**

```bash
ws --https
```

This will start the server and display output like:

```
Listening on https://127.0.0.1:8000, https://192.168.1.7:8000, ...
```

5️⃣ **Access the App on Your Device**

* Use your phone or browser and go to one of the HTTPS URLs (e.g., `https://192.168.1.7:8000`)
* Accept the SSL warning (self-signed certificate)
* Allow camera access
* Point to a printed or digital **HIRO marker** to see the AR model

---

## 🖼️ Marker Information

Use the default **HIRO marker** for testing:

* PNG: [https://raw.githubusercontent.com/AR-js-org/AR.js/master/three.js/examples/marker-training/examples/pattern-files/pattern-hiro.png](https://raw.githubusercontent.com/AR-js-org/AR.js/master/three.js/examples/marker-training/examples/pattern-files/pattern-hiro.png)
* PDF: [https://chev.me/arjs-marker-training/examples/pattern-files/hiro.pdf](https://chev.me/arjs-marker-training/examples/pattern-files/hiro.pdf)

Print it or show it on another screen.

---

## 📬 Feedback & Contributions

Feel free to fork the repo, report issues, or contribute with pull requests.
Ideas for extending the project with animated models, multi-marker support, or voice controls are welcome!

---
