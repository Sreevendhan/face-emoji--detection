
# 🤖 Face Emoji Detection using AI

This is a fun and simple Python project that detects faces in real-time using your webcam and overlays emoji images on them using OpenCV.

---

## 🧠 Features
- Real-time face detection using Haar Cascades
- Emoji overlay on each detected face
- Works with any transparent PNG emoji

---

## 🛠️ Requirements

Install the following Python libraries:

```bash
pip install opencv-python numpy
```

---

## 📁 Project Structure

```
face_emoji_detection/
│
├── face_emoji_detector.py    # Main Python script
├── emoji.png                 # Your emoji image (PNG with transparency)
├── README.md                 # Project documentation
```

---

## ▶️ How to Run

1. Place an emoji image as `emoji.png` in the same folder.
2. Run the script:

```bash
python face_emoji_detector.py
```

3. Press `q` to quit the webcam window.

---

## 📸 Emoji Image

Use transparent emoji PNGs. You can find them here:
- https://emojipng.com
- https://www.cleanpng.com/free/emoji.html

---

## 💡 Tip

Make sure your emoji image has a transparent background for better visual effect.

---

## 📄 License

This project is open source and for educational purposes.
